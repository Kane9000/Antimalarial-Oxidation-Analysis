# Antimalarial-Oxidative-Stess-Analysis
Effects of Tafenoquine and Methylene Blue on Plasmodium falciparum parasites

Introduction

It is well known that use Antimalarial drugs coincides with increased drug resistant malaira. Therefore, the evaluation of new antimalarial drugs is of great importance to prevent wide spread uncontrolled malaria infections. 

In this project, the antimalarial mechanisms of action of Tafenoquine and Methylene Blue will investigated. These are well known antimalarias that have been shown to hinder the parasites but it is unclear how these drugs effect the cells. From other organisms, these drugs have been shown to induce increased oxidative stress to the cells which is why mitochondrial and cellular oxidative stress markers have been used in these flow cytometry experiments. Plasmodium faciparum strain W2 and VPA are a species of parasites that is responsible for malaria. Bothe field isolates of malaria, W2 is known to be more drug susceptible and VPA less drug susceptible.

Method

In brief, 96 well plates are stained with fluoresent markers and analysed in a flow cytometry machine. Results from an excel sheet are analysed using Jupyter notebooks and python packages. 

Results and Discussion

As suggested from the works of Hong et.al., it was determined that culture conditions throughout the experiment must be highly controlled as normal cellular metabolism is required for the accumulation of reactive oxygen species due to antimalarial drugs as earlier experiments were not able to show increases of oxidative stress. 

The flow cytometry data suggests that parasite in the not metabolically active ring stages were more suseptible to increased of oxidative stress from Methylene blue in the mitochondria. Furthermore, the metabolically active form of the parasite, Trophozoites were found to have increased oxidative stress only in the cellular compartment of the cell induced from Tafenoquine.

As expected VPA strains showed a reduction of oxidative stress levels compared to W2 strain of parasites.

MitoSox mean fluorescence										"*" = significant increase compared to control						"-" = significant decrease compared to control				
#exp	strain	form	1 hour						2 hour						3 hour					
			TQ 10uM	TQ 2uM	MB 800nm	MB 100uM	TQ&MB hi	TQ&MB lo	TQ 10uM	TQ 2uM	MB 800nm	MB 100uM	TQ&MB hi	TQ&MB lo	TQ 10uM	TQ 2uM	MB 800nm	MB 100uM	TQ&MB hi	TQ&MB lo
60	W2	rings	ns	ns	ns	ns	-	ns	-	---	-	ns	--	--	ns	ns	****	*	*	ns
60	VPA	rings	ns	ns	ns	-	-	ns	ns	ns	**	ns	ns	ns	--	-	ns	ns	----	ns
																				
CellRox mean fluorescence																				
#exp	strain	form	1 hour						2 hour						3 hour					
			TQ 10uM	TQ 2uM	MB 800nm	MB 100uM	TQ&MB hi	TQ&MB lo	TQ 10uM	TQ 2uM	MB 800nm	MB 100uM	TQ&MB hi	TQ&MB lo	TQ 10uM	TQ 2uM	MB 800nm	MB 100uM	TQ&MB hi	TQ&MB lo
59	W2	trophozoites	****	***	ns	ns	----	ns	**	**	-	ns	--	ns	ns	****	ns	**	--	ns
59	VPA	trophozoites	ns	--	ns	ns	ns	-	*	*	-	ns	--	ns	ns	ns	ns	ns	*	ns
![image](https://github.com/user-attachments/assets/e344de5e-1cc2-405d-8f7f-a908a6f9710a)

Conclusion

In this study I have shown that Tafenoquine and Methylene blue increased oxidative stress in trophozoite cellular compartment and ring mitochondrial compartments of 2 Plasmodium falciparum strains of malaria. Interestingly, the combination of Tafenoquiena and Mythylene Blue did not increase the oxidative stress in each compartment. However, it does suggest the the combination would be effective for targeting both forms of the malaria parasite via seperate mechanisms.

References

Hong Y, Li Q, Gao Q, Xie J, Huang H, Drlica K, Zhao X. Reactive oxygen species play a dominant role in all pathways of rapid quinolone-mediated killing. J Antimicrob Chemother. 2020 Mar 1;75(3):576-585. doi: 10.1093/jac/dkz485. PMID: 31793990.
