# Peptide calculator

A free, open-source peptide reconstitution calculator. Enter the vial size (mg), the water added (mL) and the amount wanted (mcg or mg). It returns the concentration and the units to draw on a U-100 insulin syringe.

**Live page:** https://prismresearchlabs.github.io/peptide-calculator/

**Chrome extension:** [Peptide Calculator on the Chrome Web Store](https://chromewebstore.google.com/detail/peptide-calculator-recons/aeodgnglneggbkahjhdicdpogcffppie)

## The math

- Concentration: `mg/mL = vial mg ÷ water mL`
- One unit on a U-100 syringe is 0.01 mL, so each unit holds `mg/mL × 10` mcg.
- Units for an amount: `units = (amount mg ÷ mg/mL) × 100`

Example: 10 mg in 2 mL is 5 mg/mL. Each unit holds 50 mcg, so 250 mcg is 5 units.

## Reconstitution chart

| Vial | 1 mL water | 2 mL water | 3 mL water |
|---|---|---|---|
| 5 mg | 5 mg/mL · 50 mcg/unit | 2.5 mg/mL · 25 mcg/unit | 1.67 mg/mL · 16.7 mcg/unit |
| 10 mg | 10 mg/mL · 100 mcg/unit | 5 mg/mL · 50 mcg/unit | 3.33 mg/mL · 33.3 mcg/unit |
| 20 mg | 20 mg/mL · 200 mcg/unit | 10 mg/mL · 100 mcg/unit | 6.67 mg/mL · 66.7 mcg/unit |
| 30 mg | 30 mg/mL · 300 mcg/unit | 15 mg/mL · 150 mcg/unit | 10 mg/mL · 100 mcg/unit |
| 50 mg | 50 mg/mL · 500 mcg/unit | 25 mg/mL · 250 mcg/unit | 16.7 mg/mL · 166.7 mcg/unit |
| 100 mg | 100 mg/mL · 1,000 mcg/unit | 50 mg/mL · 500 mcg/unit | 33.3 mg/mL · 333.3 mcg/unit |

## Guides

- [Peptide calculator with a dose chart](https://www.prismlabs.store/reconstitution-calculator)
- [How to reconstitute peptides: 7 steps](https://www.prismlabs.store/articles/how-to-reconstitute-peptides)
- [How to read a peptide certificate of analysis](https://www.prismlabs.store/articles/how-to-read-a-peptide-coa)
- [Prism Labs lab report index](https://docs.google.com/spreadsheets/d/e/2PACX-1vTKecalBVSC7UAD4sk7OuL1kyklBUPc7xu08oM2pah-PFAY2ZWAdQqcEfz1T3h-Tf8CF1xq783P6HAp/pubhtml): lot numbers, test dates and purity for every lot

## Notes

Math only. It does not choose an amount for you and is not medical advice. For laboratory research use only.

Maintained by [Prism Labs](https://www.prismlabs.store), a US supplier of research peptides with a third-party lab report for every lot. MIT licensed.
