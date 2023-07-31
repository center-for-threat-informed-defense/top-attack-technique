# Top ATT&CK Techniques

Top ATT&CK Techniques provides defenders with a systematic approach to
prioritizing ATT&CK techniques. Our open methodology considers technique
prevalence, common attack choke points, and actionability to enable defenders to
focus on the ATT&CK techniques that are most relevant to their organization.

**Table of Contents:**
- [Getting Started](#getting-started)
- [Overview](#overview)
- [Limitations](#limitations)
- [Getting Involved](#getting-involved)
- [Questions and Feedback](#questions-and-feedback)
- [How Do I Contribute?](#how-do-i-contribute)
- [Notice](#notice)


## Getting Started

To get started, try using the web-based calculator. If you want to go deeper, review the
methodology and consult the Excel calculator spreadsheet to see the underlying data and
computations.

| Resource                                                                                                                       | Description                                                                                         |
| ------------------------------------------------------------------------------------------------------------------------------ | --------------------------------------------------------------------------------------------------- |
| [Web Calculator](https://top-attack-techniques.mitre-engenuity.org/)                                                           | A web-based calculator for building customized priority lists of techniques tailored to your needs. |
| [Methodology](https://github.com/center-for-threat-informed-defense/top-attack-techniques/blob/main/Methodology.md)            | An overview of the algorithms and analysis that went into creating the calculator.                  |
| [Excel Calculator](https://github.com/center-for-threat-informed-defense/top-attack-techniques/raw/main/Calculator.xlsx)       | The Excel version of the Top ATT&CK Techniques calculator.                                          |
| [Excel Calculator README](https://github.com/center-for-threat-informed-defense/top-attack-techniques/blob/main/Calculator.md) | Guidance for using the Top ATT&CK Techniques Excel calculator.                                      |

## Overview

The Top ATT&CK Techniques Calculator makes it easy to build customized lists of
high-priority ATT&CK techniques lists. The prioritization is based on a
[methodology](./Methodology.md) that incorporate technique prevalence, choke point
analysis and actionability.

<img width="468" alt="image" src="https://user-images.githubusercontent.com/1420025/167134772-933b2bf1-3bd2-44d0-a1c8-f27dd9e1724f.png">

Users can create a top 10 technique list tailored to their
organization. The user inputs include filters for the operating system, security
controls, detection analytics, and modifiers for process and network monitoring
coverage. The calculator displays the top 10 techniques and provides the option
to export every technique in v10 of ATT&CK in JSON format.

<img width="412" alt="image" src="https://user-images.githubusercontent.com/1420025/167134857-00f5aa70-1f32-4a31-8698-cdc4f97c8796.png">

Along with giving defenders a tool to help prioritize techniques, the project
wanted to put our methodology to practical use and produce a top 10 list that
was focused on a specific topic. A ransomware list was selected because
ransomware is wide-reaching, indiscriminate, and relevant. This list is the
Center’s assessment of which techniques a defender should prioritize to protect
themselves against a ransomware attack.

To create this ransomware list, the project’s methodology was used and
supplemented by adding a separate component that is specific to the Center’s
ransomware analysis. To feed this component, CTI (Cyber Threat Intelligence)
reporting on 22 different ransomware families was reviewed and extracted
techniques that were used during ransomware attacks. The more times a technique
was seen across the 22 groups, the higher the weight.

## Limitations

ATT&CK was never created with the intent of assigning values to each technique.
It is a compendium of things adversaries have done and gives defenders a common
lexicon. Therefore, quantifying the data within ATT&CK is a bit precarious. This
project applied discrete values to abstract ideas and generated a weighted score
for every technique.

The data used for this analysis was hardly perfect, which led to some flawed
inputs. Flawed inputs lead to flawed outputs, which means that this top 10 list
should not be seen as a declaration that you only need to defend against the top
10 techniques. This list should serve as a starting point for a more holistic
approach to systematically improving defensive capabilities.

There are certainly gaps and errors with our approach, but in the Center, we are
always trying to advance the state of threat-informed defense. This is our first
attempt at creating a methodology to prioritize ATT&CK techniques and we plan to
make improvements. To do that, we need your feedback. Please share with us what
is working, what isn’t working, and how we can make this more beneficial to you.

## Getting Involved

There are several ways that you can get involved with this project and help
advance threat-informed defense:

- **Review the methodology, use the calculator, and tell us what you think.**
  We welcome your review and feedback on the calculator and our methodology.
- **Help us prioritize improvements.** Let us know where we can improve. Your
  input will help us prioritize improvements.
- **Share your use cases.** We are interested in hearing from you about your use
  cases and ideas. Tell us how you leveage the Top ATT&CK Techniques resources
  and share your ideas for improving upon this foundation.

## Questions and Feedback

Please submit issues for any technical questions/concerns or contact
ctid@mitre-engenuity.org directly for more general inquiries.

Also see the guidance for contributors if are you interested in contributing or
simply reporting issues.

## How Do I Contribute?

We welcome your feedback and contributions to help advance our methodology.
Please see the guidance for contributors if are you interested in [contributing
or simply reporting issues.](/CONTRIBUTING.md)

Please submit
[issues](https://github.com/center-for-threat-informed-defense/top-attack-technique/issues)
for any technical questions/concerns or contact ctid@mitre-engenuity.org
directly for more general inquiries.

## Notice

Copyright 2022 MITRE Engenuity. Approved for public release. Document number
CT0047

Licensed under the Apache License, Version 2.0 (the "License"); you may not use
this file except in compliance with the License. You may obtain a copy of the
License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software distributed
under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR
CONDITIONS OF ANY KIND, either express or implied. See the License for the
specific language governing permissions and limitations under the License.

This project makes use of ATT&CK®

[ATT&CK Terms of Use](https://attack.mitre.org/resources/terms-of-use/)

