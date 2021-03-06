# OBJECTIVES

The objective behind this repo is to investigate some personal wealth management strategies, from a *theoretical perspective* considering I'm no **F**inancial **P**rofessional **A**dviser ( **FPA** ). **The initial objective** is to empower 
willing individuals with strategies available to *most citizens*, that do not benefit directly from [private wealth management advises](http://en.wikipedia.org/wiki/Wealth_management). 
**The goal** is to *integrate* the knowledge gained from our initial objective into a *custom wealth management plan optimizing one's financial goal(s)*. During that integration process, each strategy 
will be considered as a module with interaction on a main cash flow, so as to allow integration of new strategies in the future, but also to account for differences in strategies applicable to different nations' tax laws (hopefully, 
enough thoughts will be given on that front so that efforts will not be for canadians only).

By means of examples, **and living in Canada**, the *initial investigation* will involved [RRSP](http://en.wikipedia.org/wiki/Registered_Retirement_Savings_Plan) *VS* [TFSA](http://en.wikipedia.org/wiki/Tax-Free_Savings_Account) contributions, 
minimum mortgage payments *VS* anticipated contribution(s) and registered *VS* [nonregistered](http://www.investorwords.com/18431/non_registered_account.html) contributions in light of 
retirement objective(s) and tax-brackets evolution through one's professional life. A potential following *main objective* would be to incorporate all of the previous into an optimization scheme converging toward retirement 
objective(s).

Consequently, given hypothetical investment vehicles returns, the objective is to optimize the flow of cash to such vehicles through various strategies, and for a given financial objective (by default, maximizing retirement income).
 
###### MOTIVATION(s)
I've *rarely* met with FPAs providing an integrated overview of possible **usual** *custom personal financial planning* given a clear picture of current and projected assets along with desired future financial objective(s).
Rather, I've seen spreading (interesting but...) domain specific advises fitting FPAs comfort zones (... and fees criteria). 
*Do ask for a projection of your wealth at age 75, maximizing the retirement income between age 60-75, that optimizes (rather than maximizes) registered/nonregistered contributions along with optimal house mortgage structure, 
and accounting for changes in (1) tax brackets, (2) varying investments performances negative/positive on a yearly basis, (3) family income/tax management ... summarized in a nice graph/table for you to track on a yearly basis !!*

Beyond that statement, as I'm surprised no university research group came up with such framework through some *tax-payed research grant*, I've decided to address the matter and work on it.
(truth is, such research sponsored grants do exist but end up being involved in *technology transfers* that, in the end, will not directly benefit the general public in form of educating its fellow citizen).

... And finally, although I've found interesting information throughout different blogs/books, beside few random or out of context examples, I've never came across actual implementation of strategies ... *and I believe the math !* 
is the real ground on which one may assess the risk-dependency of different financial plans, **in light of FPAs' experiences** in advising different individuals and families while assessing their real ability to 
understand the nature of risk and its impact on one's quality of life.

# INVESTMENT DISCLAIMER, RISKS and WARNINGS
REFER TO [Investment Disclaimer, Risks and Warnings](RisksWarnings.md) FOR DETAILS.

## LICENSE
[ADAPTIVE PUBLIC LICENSE V1.0](http://opensource.org/licenses/alphabetical) as stated in [LICENSE.txt](https://github.com/florentchandelier/WealthManagement/blob/master/License.txt) 
with its supplement file [SUPPFILE.txt](https://github.com/florentchandelier/WealthManagement/blob/master/suppfile.txt).

*Why APL V1.0?* Beside the fact that the initial contributor may make personal choices affecting part of the license terms, **section *3.6* grants independent modules with separate license agreements**. 

Optimistically speaking, this may provide an excellent dynamic for public/private contributions, providing that modularity has been accounted for appropriately (refer to *section 1.7* of APL V1.0) during code design and development.

## CODE LAYOUT and DIRECTORIES

I will use primarily [R](http://www.r-project.org) for implementation as I believe this is a straight-forward yet extremely powerful framework in forms of scripting language for statistics. Along with the code, there should be different **.Rproj**
 files corresponding to **project workspaces** for the excellent [R-Studio IDE](http://www.rstudio.com). **Codes and Scripts validation and Verification was carried on under R-version:>3.0.0 (last test: 3.0.2) and RStudio-version:>0.97.551 (last test: 0.98.484)

Furthermore, **to preserve the confidentiality of personal financial information**, a *fictional financial situation* will be used from sourcing files in the [*FictionalFinancialSituation* directory](https://github.com/florentchandelier/WealthManagement/tree/master/StandaloneTesting/FictionalFinancialSituation), 
containing fictional Income sources, 
house value, mortgage rates and so on. As such, by duplicating such directory into a private one, one may be able to protect his/her financial information while benefiting from, and contributing to the project.

See major changes in the [CHANGELOG](../master/ChangeLog.md) *WIP for automatic generation from git-bash*

### CODE/GIT CONVENTIONS
(eventually, not yet decided: The overall git branching model shall follow the well-illustrated [successful git branching model](http://nvie.com/posts/a-successful-git-branching-model/).)

Branch naming conventions shall follow that of [GroupName/Info](http://stackoverflow.com/questions/273695/git-branch-naming-best-practices):

1. Use **grouping names** at the beginning of your branch names.
2. Define and use short **lead tokens** to differentiate branches in a way that is meaningful to your workflow.
3. Use slashes to separate parts of your branch names.
4. Do not use bare numbers as leading parts.
5. Avoid long descriptive names for long-lived branches.

Grouping Names: Short and well-defined group names (used to tell you to which part of your workflow each branch belongs):

- **wip** Works in progress; stuff I know won't be finished soon
- **feat** Feature I'm adding or expanding
- **bug** Bug fix or experiment
- **junk** Throwaway branch created to experiment
 
### DIR ~ StandaloneTesting
Contains R-scripts for **SINGLE PURPOSE INVESTIGATIONS** of specific investment strategies (such as the Smith Manoeuvre). The objective is to get a feel for different strategies prior further work.
The code itself is meant to be self-explanatory rather than optimized, with web references for definition/explanation/formulae

> REFER TO [Notes_StandaloneTesting](https://github.com/florentchandelier/WealthManagement/blob/master/StandaloneTesting/Notes_StandaloneTesting.md) FOR DETAILS.

### DIR ~ Testing
Contains R-scripts tests for the validation of created function(s) in forms of *(a)* equivalence with expected pre-calculated outcome and *(b)* equivalence with straight forward and anticipated outcome.
> REFER TO COMMENTS WITHIN SOURCES FOR DETAILS

## USAGE
Nothing is implemented yet in the general sense as [Standalone Testing](https://github.com/florentchandelier/WealthManagement/blob/master/StandaloneTesting/Notes_StandaloneTesting.md) of different Strategies is undergoing.

