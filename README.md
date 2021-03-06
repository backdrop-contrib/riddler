# Captcha Riddler

Simple but effective form spam protection.

This module lets you create custom riddles for the Captcha module,
requiring guests to answer the 'riddle' before being allowed to submit the form.

- Create your own Captcha questions to give your forms personality that matches your site
- Allows multiple possible answers for one question
- Available questions get randomly presented to people
- On multilingual sites riddles are translatable (source language is English)
- Text Captchas are better than image Captchas regarding web accessibility

## Examples

Depending on your situation, you might ask different types of questions to get
the most out of Captcha Riddler without frustating site visitors.

If people who register or fill out any forms should know certain things anyway, ask
these commonly known things, e.g.:

**Q:** What's the name of our club mascot?

If your site has a language with accents or umlauts, make sure that answers
contain these, e.g.:

**Q:** Bekannte deutsche Stadt mit Dom - K...

**A:** Köln

Or create simple groups of words where one doesn't belong, e.g.:

**Q:** Which word does not belong: cat, dog, cow, bicycle

Make sure you create a bunch of questions - the more the better.

## Installation

- Install this module using the official [Backdrop CMS instructions](https://backdropcms.org/guide/modules)

## Requirements

- Depends on the Captcha module

## Issues

Bugs and Feature requests should be reported in the [Issue Queue](https://github.com/backdrop-contrib/riddler/issues)

## Current Maintainers

- [Indigoxela](https://github.com/indigoxela)

## Credits

- Ported to Backdrop by Indigoxela
- Originally developed for Drupal by [imerlin](https://www.drupal.org/u/imerlin)
- Currently maintained for Drupal by [Oleksandr Bazyliuk](https://www.drupal.org/u/alex_optim)

## License

This project is GPL v2 software. See the LICENSE.txt file in this directory for complete text.
