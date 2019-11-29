# pm
a pool manager instance coordinates the supply of a set of remote laboratory experiments

## Features wishlist
- availability awareness
- self-check awareness
- catalogue of what is available
- indications to assist in selection such as last-used, available-until, last-checked
- two-level booking (block and user)
- fractional block-level booking
- usage accounting 

## Architectural thoughts

pool managers can potentially shield experiments from a great deal of policy changes, which suggests that pool manager inherits from both experiments and other systems. It's going to be a busy place for code, but it should make other systems easier to develop. It's possibly the case that features will incubate in pool manager before being split out, so that decisions can be based on experience and changes made before making systems heavyweight. We'll see ... .
