# [ECMAScript Internationalization API Specification](https://github.com/tc39/ecma402) proposals

 - [Stage 0 Proposals](stage-0-proposals.md)
 - [Finished Proposals](finished-proposals.md)

 [ECMAScript](../README.md) proposals

## Active proposals

Proposals follow [this process document](https://tc39.es/process-document/).
This list contains only stage 1 proposals and higher that have not yet been withdrawn/rejected, or become finished.

### Stage 3

| Proposal                                                               | Author                           | Champion                         | <sub>Last Presented</sub>                             |
| ---------------------------------------------------------------------- | -------------------------------- | -------------------------------- | ----------------------------------------------------- |
| [`Intl.DateFormat.prototype.formatRange`][formatrange]                 | Felipe Balbontín                 | Sathya Gunasekaran               | [March&nbsp;2019][formatrange-notes]                  |
| [`Intl.Segmenter`: Unicode Segmentation in JavaScript][intl-segmenter] | Daniel Ehrenberg, Richard Gibson | Richard Gibson                   | [July&nbsp;2020][intl-segmenter-notes]                |

### Stage 2

| Proposal                                                               | Author                           | Champion                         | <sub>Last Presented</sub>                   |
| ---------------------------------------------------------------------- | -------------------------------- | -------------------------------- | ------------------------------------------- |
| [`Intl.DurationFormat`][intl.durationformat]                           | Younies Mahmoud, Ujjwal Sharma   | Younies Mahmoud, Ujjwal Sharma   | [June&nbsp;2020][intl.durationformat-notes] |
| [`Intl.NumberFormat` V3][intl-v3]                                      | Shane Carr                       | Shane Carr                       | [June 2020][intl-v3-notes]                  |
| [Intl Enumeration API][intl-enumeration]                               | Frank Tang                       | Frank Tang                       | [September 2020][intl-enumeration-notes]    |
| [`Intl Locale Info`][intl-locale-info]       | Frank Tang                     | Frank Tang                     | [December 2020][intl-locale-info-notes]     |

### Stage 1

| Proposal                                                     | Author          | Champion        | <sub>Last Presented</sub>                                        |
| ------------------------------------------------------------ | --------------- | --------------- | ---------------------------------------------------------------- |
| [Smart Unit Preferences in Intl.NumberFormat][smart-units]   | Younies Mahmoud | Younies Mahmoud | [June 2020][smart-units-notes]                                   |
| [`Intl.DisplayNames v2`][intl.displaynames-v2]               | Frank Tang      | Frank Tang      | [September 2020][intl.displaynames-v2-notes]                     |
| [`Intl Locale Info`][intl-locale-info]                       | Frank Tang      | Frank Tang      | [September 2020][intl-locale-info-notes]                         |
| [eraDisplay option for `Intl.DateTimeFormat`][eradisplay]    | Louis-Aime      | Louis-Aime      | [December 2020][eradisplay-notes]                                |
| [`Intl.LocaleMatcher`][intl-localematcher]                   | Long Ho         | Long Ho         | [December 2020][intl-localematcher-notes]                        |

### Contributing new proposals

Please see [Contributing to ECMAScript](https://github.com/tc39/ecma262/blob/master/CONTRIBUTING.md) for the most up-to-date information on contributing proposals to this standard.

### Onboarding existing proposals

Proposals that are Stage 1 and above must be transferred to [the TC39 GitHub organization](https://github.com/tc39) for discoverability and archival purposes. To onboard a proposal that lives outside the TC39 organization:

1. Transfer your repository to the [@tc39-transfer](http://github.com/tc39-transfer) organization
  - if you are a TC39 delegate, but not an admin in that organization, please contact [@LJHarb](https://github.com/ljharb)
2. [@bterlson](https://github.com/bterlson), [@gesa](https://github.com/gesa), or [@codehag](https://github.com/codehag) will transfer your repository to the TC39 organization the next chance they get.

Note that as part of the onboarding process your repository name may be normalized. Don't worry, repo redirects will continue to work **as long as** you never create a fork, or a new repository, with the same name - although Github Pages redirects will be broken (please update your links!).

[intl-segmenter]: https://github.com/tc39/proposal-intl-segmenter
[intl-segmenter-notes]: https://github.com/tc39/notes/blob/master/meetings/2020-07/july-21.md#intlsegmenter-for-stage-3
[formatrange]: https://github.com/tc39/proposal-intl-DateTimeFormat-formatRange
[formatrange-notes]: https://github.com/tc39/notes/blob/master/meetings/2019-03/mar-26.md#intldatetimeformatprototypeformatrange-for-stage-3
[intl.durationformat]: https://github.com/tc39/proposal-intl-duration-format
[intl.durationformat-notes]: https://github.com/tc39/notes/blob/master/meetings/2020-02/february-6.md#time-duration-format-proposal-for-stage-1
[intl-v3]: https://github.com/tc39/proposal-intl-numberformat-v3
[intl-v3-notes]: https://github.com/tc39/notes/blob/master/meetings/2020-06/june-2.md#intlnumberformat-v3-for-stage-2
[intl-enumeration]: https://github.com/tc39/proposal-intl-enumeration
[intl-enumeration-notes]: https://github.com/tc39/notes/blob/master/meetings/2020-09/sept-22.md#intl-enumeration-api-for-stage-2
[smart-units]: https://github.com/tc39/proposal-smart-unit-preferences
[smart-units-notes]: https://github.com/tc39/notes/blob/840c700dc7fa7b9f6d0a3c208bd66b333e304717/meetings/2020-06/june-4.md#smart-unit-preferences-in-intlnumberformat-for-stage-1
[intl.displaynames-v2]: https://github.com/tc39/intl-displaynames-v2
[intl.displaynames-v2-notes]: https://github.com/tc39/notes/blob/master/meetings/2020-09/sept-23.md#intldisplaynames-v2-for-stage-1
[intl-locale-info]: https://github.com/tc39/proposal-intl-locale-info
[intl-locale-info-notes]: https://github.com/tc39/ecma402/blob/master/meetings/notes-2020-12-04.md#intl-locale-info
[eradisplay]: https://github.com/Louis-Aime/proposal-intl-eradisplay
[eradisplay-notes]: https://github.com/tc39/ecma402/blob/master/meetings/notes-2020-12-04.md#eradisplay-option-for-intldatetimeformat-for-stage-1
[intl-localematcher]: https://github.com/longlho/proposal-intl-localematcher
[intl-localematcher-notes]: https://github.com/tc39/ecma402/blob/master/meetings/notes-2020-12-04.md#intllocalematcher-for-stage-1
