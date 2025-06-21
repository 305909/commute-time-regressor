<img src="docs/logo.png" width="300"/>

# The Data Didn’t Care About Income: A Story About Commutes and What We Think We Know

##### by Francesco Giuseppe Gillio
###### Department of Control and Computer Engineering
###### Politecnico di Torino

## Reference Paper
- [The Data Didn’t Care About Income: A Story About Commutes and What We Think We Know](https://github.com/sencosx/commute-time-regressor/blob/main/docs/commute-time-regressor-ACM.pdf)

---

## Table of Contents

- [What’s the Problem? (Abstract)](#whats-the-problem-abstract)
- [The Tools of the Trade (Algorithms)](#the-tools-of-the-trade-algorithms)

---

## What’s the Problem? (Abstract)

We set out to answer a simple question: can we predict how long people spend commuting, just by looking at census data? To do that, we ran a series of regression analyses on a big dataset—more than 130,000 entries—cleaned it up, stripped out the noise, and fed it into different predictive models. We tried Random Forests, Decision Trees, and Support Vector Regression, to see which one could make the best guesses and tell us which factors really matter. Turns out, Random Forest won hands down, giving us the best results by far.
    
The real game-changer wasn’t income or education—those barely moved the needle. What mattered most were the basics: what time people leave, what time they arrive, and the time between. That last one, which we called Commute Time to Work (CTTW), turned out to be a key feature. Once we added it, Random Forest nailed it, pushing R2 close to 0.997.
    
In short, if you want to know how long a commute will take, don’t ask about a person’s degree or paycheck—just find out when they leave and when they get there. The rest, we found, is mostly noise.

---

## The Tools of the Trade (Algorithms)

Play time starts here.

1. Fire this up in your notebook:

```python
!git clone https://github.com/sencosx/commute-time-regressor.git
```

2. Run the regressor and see what happens:

```python
!python /content/commute-time-regressor/regression-model.py
```

Boom. **Game over**.

---

> *“If your code always makes sense to you, you're either an idiot — or not thinking hard enough.”*

That’s what this project is about. Now go dig in.

— *F.G.G. (still writing code, as always)*
