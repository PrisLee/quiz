# quiz

An interactive, self-paced course on the [IDG Product Thinking learning pathway](https://www.idg.gov.sg/product-thinking/).

Eight illustrated lessons summarising the pathway's frameworks — the Five Whys, the 4Cs, SMART, leading and lagging indicators, the value-cost ratio, staged de-risking, and the 11-star framework. Each lesson carries a hand-drawn SVG diagram of the mechanism it teaches and ends in a multiple-choice question, with the explanation for the correct answer shown whether or not you got it right.

Each lesson has its own colour, carried through the progress pips, the lesson header, the diagram accents and the question card, so the pathway reads as a sequence rather than eight identical pages.

## Running it

Open `index.html` in a browser. No build step, no dependencies.

```
open index.html
```

## Notes

- Progress is stored in `localStorage`, so it stays in the browser and is never sent anywhere.
- Diagrams are hand-authored inline SVG — no charting library, no external images. They scroll horizontally on narrow screens to stay legible.
- Worked examples marked *illustrative* were written for this course. Direct quotes and case-study figures (including the 0-vs-24 booking A/B test) come from the source modules.
- The source pathway has 7 modules; the Metrics module is split across two lessons here so there are 8 questions.
