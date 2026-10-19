# Peer Feedback — Practice 9 Step 4.02 (Simulated Classmate Review)

**Reviewer:** Fong Hio Lam(simulated for the "Test and Improve" exercise).
**Site reviewed:** https://fongchinwai-vivi.github.io/data-science-portfolio/

## Purpose of this portfolio

- It presents Fong Chin Wai (Vivi) as a data science student and links coursework to
  evidence: a regression project and a Macau transport demand study.
- Each case card follows the same structure (Problem / Method / Result / Deliverable),
  which makes the purpose of the page easy to grasp in one scroll.
- The hero and the cross-link to the project site make the two repositories feel like
  one coherent portfolio.

## Main findings I can identify

- The regression project shows that engine size (r = 0.872) and square footage dominate
  price, and that Ridge + GridSearchCV improves the test-set R².
- The Macau transport project shows an uneven supply–demand match: Taipa & Cotai 0.507,
  Peninsula 1.577, Coloane 2.988, with visitor demand peaking at 16:00 vs bus departures
  at 08:00.
- The page is readable for someone who has not seen the notebooks.

## Limitations I would point out

1. The case cards do not state limitations; the regression caveat (1985 data) is only
   visible on the project site, and the transport study's scope limits are not mentioned
   at all on the portfolio page.
2. The transport study uses bus departures as the supply proxy; private cars, taxis,
   light rail and walking are not considered, and the data window is limited.
3. The regression case claims an R² improvement after regularisation but does not show
   the number on the portfolio card, so the claim is less convincing on its own.

## Improvement implemented in Step 4.03

- Added a "Limitation" line to both case cards so the portfolio itself is honest about
  the boundaries of each project.
