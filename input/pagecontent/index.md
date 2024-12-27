### Introduction

This IG helps with structured data of health data which can be made available in the Swiss EPR.

1. Vaccination data

Vaccination is the the first structured data which can be share in the Swiss EPR. eHealth Suisse provides a module
which allows to document immunization administrations, see documentation in [german](https://www.e-health-suisse.ch/en/latest-news/impfausweis-im-epd), [french](https://www.e-health-suisse.ch/fr/nouveautes/carnet-de-vaccination-dans-le-dep) or [italian](https://www.e-health-suisse.ch/it/novita/certificato-di-vaccinazione-nella-cip).

The vaccination administrations are stored as documents according to the FHIR CH VACD [exchange formats](https://fhir.ch/ig/ch-vacd/index.html).

See further example data [here](vacd.html)


### Source and Download

[GitHub Repository](https://github.com/oliveregger/ch-epr-data-oe)

**Download**: You can download this implementation guide in the [NPM package](https://confluence.hl7.org/display/FHIR/NPM+Package+Specification) format from [here](package.tgz).

### IP Statements
This document is licensed under Creative Commons "No Rights Reserved" ([CC0](https://creativecommons.org/publicdomain/zero/1.0/)).

HL7®, HEALTH LEVEL SEVEN®, FHIR® and the FHIR <img src="icon-fhir-16.png" style="float: none; margin: 0px; padding: 0px; vertical-align: bottom"/>&reg; are trademarks owned by Health Level Seven International, registered with the United States Patent and Trademark Office.

This implementation guide contains and references intellectual property owned by third parties ("Third Party IP"). Acceptance of these License Terms does not grant any rights with respect to Third Party IP. The licensee alone is responsible for identifying and obtaining any necessary licenses or authorizations to utilize Third Party IP in connection with the specification or otherwise.

{% include ip-statements.xhtml %}

### Cross Version Analysis

{% include cross-version-analysis.xhtml %}

### Dependency Table

{% include dependency-table.xhtml %}

### Globals Table

{% include globals-table.xhtml %}
