---
title: Residency
parent: Personal Income Tax
grand_parent: Tax in Canada
math: mathjax3
nav_order: 1
layout: default
---

<div class="page status" markdown="1">
Completed for Now
{: .label .label-blue }
</div>

# **Am I Subject to Income Tax in Canada?**

This is the 1st question that should be asked. Otherwise, there is no point reading further.

## Worldwide Income Taxable

Unlike the United States which determines whether you are subject to income tax on your *worldwide income* based on citizenship and residency, the only criteria used in Canada is your **residency** status.

In other words, in Canada tax system, you are subject to income tax for all income and gains originated anywhere in the globe, as long as you are a **resident of Canada**, even if you are **NOT a Canadian citizen**.

Otherwise, if you are not a resident, only specific activies occurred in Canada will be taxed.

## **How do I know if I am a "Resident"**

This is determined on a year-by-year basis.
If there was no immigration activity during the year, there are 2 ways of knowing it:

1. ***Deemed Resident***

    If you have stayed in Canada for **more than 182 days** in the **calendar year**.

2. ***Residency based on Common Law***

    Discussed further below.

### Mechanism
The process effectively works like this:

```
def Residency(individual){

# return if the individual given is a resident of Canada for tax purposes, assuming no immigration activity.

    If (individual.getStays() > 182){
        return True;
    } else{
        return ResidencyCommonLaw(individual);
    }
};
```

### **Tax Residency under Common Law**

Your residential ties with Canada is defined as whether you have "continuing relationship with Canada".

In human language, it is judged based on the following factors:

(Text in *Italic* is how I personally call them).

1. **Significant Residential Ties**
    
    - *family ties*

        - Home in Canada.
        - Spouse or partner or children living in Canada.

2. **Secondary Residential Ties**

    - *Economic ties*
        - Personal properties in Canada. (e.g. cottage, car, ...)
        - Canadian bank account
        - Canadian credit card
    - *Social ties*
        - gym membership
        - professional organizations
        - religious groups
    - *Legal ties*
        - Canadian passport
        - Canadian driver license
        - Canadian provincial health card

**NOTE**: It does not mean that if you have a Canadian passport, you are a resident of Canada.

The residential ties above are factors used in court, so it is more of a judgement thing with no crystal-clear critiera, unlike the deemed resident rule.

In the court, other factors will also be considered such as motives, background, routine of life, and so on. 

Whether you are a resident is sometimes quite obvious, and sometimes not. ***If in doubt, consult a professional.***

### **Part-Year Resident: Immigration & Emmigration**

A special situation is when someone immigrates into or emmigrate out of Canada during a calendar year.

The residency status is obvious by itself. If you are immigrating into Canada, you are certainly becoming a Canadian resident, and vice versa.

However, you are only considered a **Part-Year Resident** for the period that you are a Canaidan resident.

> Example #1:
>
> Alex immigrates into Canada as an international student temporary resident starting September 1st of 2022. He is a part-year resident of Canada from September 1st to December 31, for the 2022 tax year.


#### Practical Implication

- For the period that you are **resident**, your **worldwide income during that period** will be taxable in Canada.
- For the period that you are **non-resident**, only **certain Canadian activities during that period** will be taxable in Canada.
- Some tax credits eligible for **residents** will be reduced proportionally based on the number of days.

> Example #2:
> 
> Each individual taxpayer is eligible for a tax credit called *Basic Personal Amount*, which is around $13,000 each year. (The exact amount changes each year).
> 
> In the case of Alex in Example #1, he is only a Canadian resident for 121 days, the *Basic Personal Amount* for him will be: $$ \$13,000 \times ( 121 \thinspace days / 365 \thinspace days ) = \$4,309 $$

Tax credits that are based on certain income or expenses will not be affected. Only those that are based on the passage of year will be reduced proportionally in the situation above, such as Basic Personal Amount, Canadian Employment Amount, and so on. Details about tax credits will be discussed in the future.

