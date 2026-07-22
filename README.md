# UK Tax Rules (Machine-Readable)

Open dataset of UK personal tax thresholds, rates and rules in JSON.
Maintained for use in calculators and financial tooling.

## Why
UK tax data is published across dozens of GOV.UK pages in prose form.
This repo keeps it versioned, machine-readable and diffable year over year.

## Coverage
- Income Tax (rUK + Scotland)
- National Insurance (Class 1, 2, 4)
- Student Loan (Plans 1, 2, 4, 5, PGL)
- Stamp Duty / LBTT / LTT
- Dividend & Capital Gains

## Used by
These rules power the calculators at [Qalqlet](https://qalqlet.com/uk/),
where each result links back to its source and rule version.

## Sources
Every file carries a `source` field pointing to the primary GOV.UK or official government page
and a `last_reviewed` date.

## Licence
MIT — free to use with attribution.

## Topics
uk, tax, open-data, json, hmrc, finance
