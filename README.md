# docsify-test

This is a sample repo to test out docsify.

## Emojis

I've noticed an issue with the way emojis are rendered within links. For example:

- https://link.com/:smile:/index - anchor tag's href should not be parsed as an emoji
- [:smile:](https://link.com/:smile:/index) should have its content parsed as an emoji, but the href should not be parsed as an emoji
