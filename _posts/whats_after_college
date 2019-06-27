---
layout: post
title: What's After College
subtitle: My first Lambda School Project
---

If there were a Venn diagram of people who have had a conversation with me in
the past two years and people who know my opinions about American education,
that Venn diagram would be an almost-perfect circle.

![](https://cdn-images-1.medium.com/max/1000/0*NQxSjRNO2zrUXyiU)
<span class="figcaption_hack">Like this shape but a little less artistic. — PC: Jeremy Perkins</span>

I get *heated* about education, in all forms. It’s a big part of why I’m so
passionate about Lambda School — their model fixes a lot of the problems I have
with the collegiate education system.

So when my time came in Lambda to work on my first project — any open-ended
thing, as long as it involved data available to me — my topic choice was
obvious: education.

Hours of Googling later, and I found it: a beautiful
[dataset](https://ed-public-download.app.cloud.gov/downloads/Most-Recent-Cohorts-Scorecard-Elements.csv)
from [Scorecard](https://collegescorecard.ed.gov/) which contained 190 columns
of information about 7058 different American colleges and universities. Here’s
what I learned from it.

<span class="figcaption_hack">What I imagined 8 AM classes would be like — PC: Ben Duchac</span>

College isn’t as carefree as stock photos would have you believe. I know, you’re
shocked. Bear with me. College students are graduating with large amounts of
debt (again, no one is surprised). But, here’s the real issue: students are then
moving on to almost no income. The six-figure jobs they were promised seem like
a fever dream when compared to the average income, which is barely 25% over
poverty level, if you’re lucky.

But I’m getting ahead of myself. First, the data. (P.S., you can see my full
work [on
Github](https://github.com/AnikaZN/DS-Unit-1-Sprint-5-Data-Storytelling-Blog-Post/blob/master/Race_and_Education.ipynb))

I started with the messiest dataset I’ve ever worked with, and I’m not ashamed
to say it was pretty fun to clean that bad boy. My favorite part was tracking
down the Excel spreadsheet which held translations for all of the nonsense
column labels I was looking at, like “CIPTFBSANNUAL6,” which means “Tuition,
fees, books, and supply charges for program #6 (annualized based on
institution’s academic year).” Of course. Once I had those translations, I was
then able to update the dataframe to reflect the more readable names I came up
with, such as “historically_black” and “undergrads_25+”

<span class="figcaption_hack">The first few lines of my now-clean dataset</span>

From there, I started to explore. Using the skills I’ve learned at Lambda so
far, I made several graphs of the data, ran a few t-tests (for those unfamiliar
with statistics, that basically means that I evaluated the odds that the
relationships in the data were nothing but random), and ran lots of .astype
lines (the computer seemed to think that all of my numbers were not numbers).

I settled on looking at the relationships between students’ graduation rates
(within 8 years), debt upon graduation, and income ten years after enrollment,
sorted by the student’s race/ethnicity.

First, a note: “Other” refers to students who identify as American Indian,
Alaskan Native, Pacific Islander, Native Hawaiian, two or more races, or
students who chose not to designate their race.

### **Graduation Rates**

The first obvious thing is that the “Other” category has the smallest percentage
of graduates, with an average of only 42% of students completing within 8 years.
No other demographic category had less than 50% of students graduate, and I have
to admit I was unimpressed by the proof that America continues to fail our
Native population. Still, though, I think another major focus point here is how
few students are graduating, regardless of race. Asian students performed the
best on average, with 57% graduating, and that is still difficult to celebrate.
On average, if you took a random group of 10 college freshmen, only 5 of those
freshmen would graduate within ten years*. *[Compare that to even the year 2000,
and it’s dropped by about
8%.](https://en.wikipedia.org/wiki/Decreasing_graduation_completion_rates_in_the_United_States#/media/File:NCES_USA_College_Graduation_Rates_1996-2012.png)

### **Debt**

Again, we notice that the “Other” category gets the short end of the stick here,
graduating with the highest amounts of debt. So, as a reminder, students who
presumably had to work the hardest to graduate then do so with an average of
just over $18,000 in debt. (Don’t forget that students who don’t graduate still
are expected to pay back any debt they’ve incurred.)

Even Hispanic students, who graduate with the least amount of debt on average,
are walking out of school owing just shy of $12,500. This is the minimum price
we ask our students to pay (not accounting for tuition payments while they’re in
school), with the guarantee that it’s the only way for them to get a well-paying
job after school.

Is that really a guarantee, though?

### **Income**

You’ll notice that this graph is a bit different from the others. That line at
about $25,000 demarcates the American poverty line for a family of 4 in 2018. I
will also call your attention to the fact that this is the income of students
who graduated ten years after they first enrolled in college, which means this
is the average income for a 28-year-old college-educated student 6 years after
they finish a Bachelor’s degree. Assuming that their income increases at a rate
of 3% a year, this means that they entered the job force making *barely* enough
to be considered not in poverty.

So, an 18-year-old decides to go to college. They accrue $16,542 in debt over
the course of 4 years. We’ll assume they graduated and land a job fresh out of
college; maybe it’s in the field they studied and maybe it isn’t. Their starting
salary is $27,000 (or $13/hour). They work hard and consistently pay 5% of their
pre-tax income towards their loans (we’ll assume this is a very responsible
person and they found a place with cheap rent). By the time they’re 28 years
old, 10 years after they made that first choice to go to college, they’ll be
making only about $5,000 more annually and will still have $11,360 in debt
remaining. It will take them another 7 years to completely pay off their student
loan debt.

<span class="figcaption_hack">A bit of stress relief for you in case you are also yelling at your computer. —
PC Matthew Henry</span>

So, to answer my initial question, the post-college prospects for students are
less than ideal right now, to say the least. Work is being done and
conversations are being had, but we need to implement change now.

I, for one, am grateful not only for the eye-opening opportunity this was,
grateful for an excuse to dive deep and see how truly flawed our current system
is, but I am also grateful for Lambda School changing the game for me and
hundreds of other students. I promise you that this is not an ad, but it may as
well be: Lambda is a real alternative, and Lambda is doing higher education
right.

Go hug a college student in your life. Maybe buy them a coffee. They need it.
