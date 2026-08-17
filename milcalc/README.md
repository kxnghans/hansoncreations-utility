# MilCalc

MilCalc is an offline calculator app for US service members. It handles Air Force PT scores, military pay with BAH and BAS estimates, and retirement comparisons (High-3 vs. BRS) directly on your device without creating an account or transmitting personal data.

## Features

### Air Force Physical Fitness Assessment
Scoring calculations based on official DAFMAN 36-2905 standards:
- **Cardio & Muscular components**: 1.5M run, 2.0M run, 20M HAMR, push-ups, hand-release push-ups, sit-ups, cross-leg reverse crunches, and forearm planks.
- **Altitude adjustments**: Automatic score corrections based on base elevation.
- **Exemptions**: Calculates composite scores across valid components when specific events are medically exempted.
- **Risk metrics**: Waist-to-Height Ratio (WHtR) and cardio category tracking.

### Pay & Allowances
Monthly and annual pay estimates for active duty, Guard, and Reserve:
- **Pay tables**: Current DFAS basic pay, BAH (with and without dependents), and BAS rates.
- **Drill pay**: UTA and annual training estimates for drilling Guard and Reserve members.
- **Taxes**: Federal, FICA, and state tax estimates, with customizable deduction inputs.
- **Special pays & VA offsets**: VA disability compensation modeling and Concurrent Retirement and Disability Pay (CRDP) calculations.

### Retirement Modeling
Side-by-side comparison of legacy and modernized military retirements:
- **Blended Retirement System (BRS)**: TSP monthly compounding projection with government 5% matching and continuation pay estimates.
- **High-3 Pension**: Multipliers based on years of service and highest 36 months of basic pay.
- **Guard/Reserve Retirement**: Point calculation conversions and reduced retirement age tracking for qualifying Title 10 active service deployments.

## Design & Privacy Principles

- **Offline by default**: All calculation engines run locally on SQLite and in-memory caches. You do not need cell service or Wi-Fi on the flightline, shipboard, or in the field.
- **Zero data collection**: No accounts, no emails, no analytics beacons, and no tracking scripts. Inputs stay on your phone.
- **Direct feedback**: Neumorphic interface optimized for fast inputs with one hand.

## Documentation & Support
- Web: [hansoncreations.com](https://hansoncreations.com)
- Bug Reports: [hansoncreations.com/bug-report](https://hansoncreations.com/bug-report)
- Terms of Use: [TERMS.md](./TERMS.md)
- Privacy Policy: [PRIVACY.md](./PRIVACY.md)
- Support & FAQ: [SUPPORT.md](./SUPPORT.md)

