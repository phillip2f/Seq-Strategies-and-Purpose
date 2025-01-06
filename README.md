# Association-Between-Sequential-Persuasion-Strategies-and-Basic-Psychological-Needs

## Code Structure
We will release our code after our paper has been published.

## Data
The r/borrow dataset is from this [repo](https://github.com/SALT-NLP/Persuasion_Strategy_WVAE/tree/main)

## The Patterns
We list all the top 3 positive and  negative patterns with their average success rates, increasing values and support values.


## The Rrompt for rewriting
Here is the sample of rewriting:

<img src="rewrite-demo.jpg" width="70%">

We demonstrate the example of applying credibility and reciprocity strategy on the rewrite discourse by different LLMs:

**Gemini-1.5:**
I have a pretty consistent history of repaying loans on time, if not early. *There is one that the lender accidentally marked as "Late", however he's apologized and annotated so!* (**credibility strategy**)
*With the added interest, the full repayment will amount to \$35.* (**reciprocity strategy**)

**GPT-4o:**
*My track record here is strong, which I hope will inspire confidence in my request.* (**credibility strategy**)
*If anyone could kindly lend me the money, I assure you that I will repay it promptly.* (**reciprocity strategy**)

**Claude-3.5:**
I've consistently maintained financial stability and have never needed to borrow before, which speaks to my fiscal responsibility. 
*My track record of managing my finances prudently should provide assurance to potential lenders*  (**credibility strategy**)
*I'm willing to offer 10\% interest on the loan, repaid in two installments on March 25th and April 10th. This is a chance to not only help a hardworking couple but also earn a return on your generosity.* (**reciprocity strategy**)

**Doubao-pro:**
*I am a responsible borrower with a consistent repayment history.*  (**credibility strategy**)
*In return for your kind loan, I'll offer an additional token of appreciation.* (**reciprocity strategy**)

**LLaMa-3.1:**
*I'm a responsible borrower with a proven track record of timely payments, having consistently made on-time payments on my current loan.*  (**credibility strategy**)
*If you were to lend me \$30, I'd be able to repay it with an added interest of \$5, making the total repayment \$35.* (**reciprocity strategy**)
