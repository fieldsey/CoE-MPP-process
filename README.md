# TTS MPP
## Welcome Guide

The information in this Welcome Guide should give anyone enough information to understand how the TTS MPP works, how someone can participate in the process, and how to replicate it and adapt it for their own purposes. Please give any and all feedback you have through our "[indefinite RFI](https://forms.gle/Lo38qwjTyE7hCPUG7)", which we will never close. Thank you!

## Introduction

The Technology Transformation Services (TTS) has an established history of experimenting with the use of micro-purchases for services and other needs.[1, 2, 3, 4] With the introduction of a $10,000 micro-purchase limit as of Fiscal Year 2018[5] along with the experiences of the Department of Veterans Affairs (VA)[6], it is an experiment worth trying again. The TTS MPP has been set up to do just that.

With the TTS MPP, various project teams throughout TTS can build a community of private sector partners that can assist them on a per sprint basis, completing work associated with individual and unique user stories. This includes help developing and testing application programming interfaces (APIs), building out existing applications, creating documentation, and developing standards and policies.

Additionally, the minimum requirement that participating contractors [register with SAM.gov](https://beta.sam.gov/signup), the government benefits from expanding the [SAM.gov](https://beta.sam.gov) network while also encouraging non-traditional government contractors to take the first step to join the contractor ecosystem.

The TTS MPP is not unique in the fact that documenting and sharing best practices in an open and transparent fashion is a key part of what makes the process repeatable and scalable. As always, we look to improve what we do as often as we can. Any feedback would be greatly appreciated!

1. [18F Micro-purchase Marketplace](https://micropurchase.18f.gov/), which is currently archived.
2. [18F Micro-purchase insights](https://micropurchase.18f.gov/insights.html), which provides data related to the marketplace’s operations.
3. [18F Blog posts tagged with "micro-purchase platforms"](https://18f.gsa.gov/tags/micro-purchase-platforms/).
4. [cloud.gov’s micro-purchases on GitHub](https://github.com/18F/cg-product/tree/master/micro-purchases).
5. [Class Deviation 2018-01](https://www.gsa.gov/cdnstatic/Policy_Initiatives/Class%20Deviation%202018-01%20MPT%20and%20SAT%20Increase.pdf), which increased the micro-purchase threshold to $10,000.
6. [VA Micropurchase Repo on GitHub](https://github.com/department-of-veterans-affairs/VA-Micropurchase-Repo).

## How it works
### Before you begin
#### Team dynamics
The TTS MPP isn’t for every project or every team. In order for the TTS MPP to be successful for you, your team must operate in either one- or two-week sprints, have well defined user stories, and strictly adhere to the idea that no individual request should span more than one sprint.

At a minimum, TTS MPP project teams should provide access to the project team’s Director for necessary approvals (Supervisor) and a technical subject matter expert that will be able to answer questions related to the need (SME). Each member of the project team, whether involved with the buy or not, should be familiar with the [agile manifesto](https://agilemanifesto.org/), the [Digital Services Playbook](https://playbook.cio.gov/), and [user stories](https://www.mountaingoatsoftware.com/agile/user-stories).

#### Tools to use
The use of a collaboration tool, such as [Trello](https://www.atlassian.com/software/trello), [JIRA](https://www.atlassian.com/software/jira), [Smartsheet](https://www.smartsheet.com/), or [GitHub Project boards](https://help.github.com/en/articles/about-project-boards), will allow for the user stories to be discretely defined and backlogs to be appropriately groomed.

### 1. Identifying a user story
#### Finalize the user story
Prior to submission to the TTS MPP, the project team should agree among themselves that their user story is independent enough such that it can be completed by a contractor without the need to access anything other than publicly available information and that the failure of a contractor to complete it will not result in a delay to or failure of a project itself.

The project team will assign a SME to serve as the product owner and the one person the TTS MPP purchase team can reach out to should there be any questions.

#### Create a draft procurement package
The project team will use TTS MPP-developed templates to create first drafts of the following documents:

1. [A market research report](https://github.com/fieldsey/TTS-MPP-process/blob/master/Documentation/Market%20Research%20Report%20-%20%7B%7BUser-Story-Title%7D%7D.docx).
2. [An independent government cost estimate](https://github.com/fieldsey/TTS-MPP-process/blob/master/Documentation/IGCE%20-%20%7B%7BUser-Story-Title%7D%7D.xlsx) (IGCE).
3. [A streamlined acquisition plan](https://github.com/fieldsey/TTS-MPP-process/blob/master/Documentation/Streamlined%20Acquisition%20Plan%20-%20%7B%7BUser-Story-Title%7D%7D.docx).

#### Confirm funding
Using [the template](https://github.com/fieldsey/TTS-MPP-process/blob/master/Documentation/TTS%20MPP%20-%20New%20User%20Story%20form%20(Approval%20email%20template).docx) created for use with the TTS MPP, the project team will obtain emailed approvals, confirming that the Supervisor has approved paying for the project and the finance team has verified the project team has the budget for the buy.

The amount approved by the Supervisor and the finance team *must* be the same amount in the IGCE.

#### Submit the user story package
The SME should submit the user story, using the [New User Story form](https://github.com/fieldsey/TTS-MPP-process/blob/master/Documentation/TTS%20MPP%20-%20New%20User%20Story%20form%20-%20Google%20Forms.pdf).

Once the SME receives a response receipt, the procurement administrative lead time (PALT) for internal use will begin. The PALT will be measured in three parts: first, from the moment a user story was submitted through the form and when the request for responses to the user story goes live on GitHub; second, from the moment the user story goes live on GitHub to the moment a contractor is chosen; and, third, from the moment a contractor is chosen and the user story is considered completed with payment approved.

These three PALTs will allow the TTS MPP purchase team to measure and improve upon their performance while also allowing the project team to set their own expectations related to how long the process will take.

#### TTS MPP reviews the need
The TTS MPP acquisition project manager (Acquisition PM) will be responsible for reviewing submissions from the New User Story form, creating a new Trello card following [the template card](https://trello.com/c/4WOg1WVu/4-template-card) provided in the [TTS MPP Trello board](https://trello.com/b/6JUMyVBx/tts-mpp-board-template). The card will be assigned to the project team’s Supervisor and SME and the purchase team’s PM and acquisition expert.

The PM will work with an Acquisition Lead, a subject matter expert in the contracting process (eg, a warranted Contracting Officer or a former 1102). The two together make up the purchase team. They are responsible to review the user story and ensure it is discrete, appropriately scoped, and contains all the information necessary for an Issue to be posted to the TTS MPP template repository.

The purchase team may require information related to the project’s development practices and backlog-related processes for the official contract file. This documentation will help mitigate risks associated with potential protests.

#### Starting the process
Once the purchase team has been able to verify everything required has been provided, [a purchase folder](https://github.com/fieldsey/TTS-MPP-process/tree/master/Purchase%20folder) will be created by the PM.

The purchase folder will have the notes file in the root folder and contain the following subdirectories:

* Procurement package
   * A copy of the New User Story form submission.
   * A PDF of the approval email thread.
   * A draft market research report using the template provided.
   * A draft IGCE using the template provided.
   * A draft streamlined acquisition plan using the template provided
* Issue package
   * A subfolder for responses containing a Google Form to collect those submissions.
   * A document to collect the questions and answers (Q&A) submitted through the Issue.
   * Templates for the following:
      * New Issue email - An email to send to the contractor community who have subscribed to the TTS MPP mailing list, informing them the Issue has been posted.
      * New Issue tweet - A tweet to promote the Issue to the general public.
      * End of Q&A comment - A comment to post in the Issue once the Q&A period has ended (if applicable).
      * End of advertising period - A comment to post in the Issue once the response period has ended.
* Award documentation
   * The award decision memorandum.
   * Templates for the following:
      * Award issued comment - A comment to post in the Issue once an award has been issued.
      * Awardee email - An email to send to the Awardee, informing them of the award and confirming the period of performance.
      * Deliverables accepted comment - A comment to post on the merge request of the fork with the deliverables.
* Deliverables
   * The only files in this folder should be those provided by the awardee.
* Closeout documentation
   * A copy of the verification that the payment was processed.

Should there be a need for a Request for Information (RFI), the TTS MPP purchase team will work with the Supervisor and SME to publish a draft Issue and Google Form for collecting feedback on the TTS MPP template repo. This documentation will be contained within the `Procurement package` subfolder in an `RFI` folder.

The RFI folder will contain draft versions of everything that the project team wants to obtain feedback on. As a result, the exact files will differ on a project-by-project basis.

The PM will tag the Supervisor and SME, where applicable, throughout the documents. Once all portions of each document are completed and there are no more suggested changes or comments, the package will be considered finalized and sent to the Supervisor and SME for a final review.

### 2. Advertising the request
#### Setting the timeline
The PM will work with the Supervisor and SME to set the timeline for the posting of the Issue, the end of the Q&A period (if applicable), and the end of the response period. Once this timeline is finalized, the Issue will be ready to be posted.

#### Posting the Issue
Once the purchase team and project team have agreed everything is finalized, an Issue will be created in the TTS MPP public repo.

The PM will also notify contractors through [an update](https://github.com/fieldsey/TTS-MPP-template#opportunities) to the TTS MPP public repo `README.md` file, an email to the listserv created for the purposes of notifying contractors who wish to participate, and, if applicable, the TTS MPP Twitter account or other appropriate Twitter account.

#### Responding to questions
The PM will gather any questions asked by the contractor community and post them in the [Issue Q&A document](https://github.com/fieldsey/TTS-MPP-process/blob/master/Documentation/Issue%20Q%26A%20-%20%7B%7BUser-Story-Title%7D%7D.docx). Once the SME and Supervisor provide and sign off on an answer, the PM will respond via the comments in the Issue.

### 3. Issuing an award
#### Reviewing the responses
The PM will work with the Supervisor and the SME to select the best of the submitted responses. Once the review is completed, an [award decision memorandum](https://github.com/fieldsey/TTS-MPP-process/blob/master/Documentation/Award%20decision%20memorandum%20-%20%7B%7BUser-Story-Title%7D%7D.docx) must be completed and submitted by the project team to the PM.

#### Announcing the award
The PM will post a [comment announcing the award](https://github.com/fieldsey/TTS-MPP-process/blob/master/Documentation/Award%20announcement%20templates%20-%20%7B%7BUser-Story-Title%7D%7D.docx), close the Issue, remove the reference to the Issue on the TTS MPP public repo’s main `README.md` file, and [email the awardee](https://github.com/fieldsey/TTS-MPP-process/blob/master/Documentation/Award%20announcement%20templates%20-%20%7B%7BUser-Story-Title%7D%7D.docx).

#### Finalizing the repos
The PM will create [a new folder](https://github.com/fieldsey/TTS-MPP-template/tree/master/yyyy-mm-dd%20User-Story) for the user story in the public repo and add a `[README.md](https://github.com/fieldsey/TTS-MPP-template/blob/master/yyyy-mm-dd%20User-Story/README.md)` file, building on the Issue, and create another subfolder for [the deliverables](https://github.com/fieldsey/TTS-MPP-template/tree/master/yyyy-mm-dd%20User-Story/Deliverables).

### 4. Approving deliverables
#### No kickoff needed
The Issue itself should contain as much information necessary for a contractor to complete the task without the need for any additional information or a kickoff meeting. The period of performance begins once the awardee is notified that they won, unless otherwise agreed upon by the teams or outlined in the Issue itself.

#### Accepting the deliverables
The Supervisor and SME will notify the PM once the deliverables have been completed in accordance with the [Definition of Done](https://github.com/fieldsey/TTS-MPP-template/tree/master/yyyy-mm-dd%20User-Story#definition-of-done) associated with the user story. Upon receipt of this notification, the PM will post [a comment](https://github.com/fieldsey/TTS-MPP-process/blob/master/Documentation/Award%20announcement%20templates%20-%20%7B%7BUser-Story-Title%7D%7D.docx) in the contractor’s merge request, indicating acceptance of the deliverables.

#### Process the payment
The PM will request payment be made to the contractor.

### 5. Closing out the buy
#### Verifying payment
The PM will obtain confirmation of payment (eg, an email from the contractor confirming receipt, a “paid” invoice, etc.). The confirmation should be printed and filed in the `Closeout documentation` folder.

#### Archiving the purchase folder
The PM will rename or move the user story’s purchase folder to make it clear it has been delivered.

## Data to be collected and shared
### Platform-wide metrics
This data will be reported to the public in the [INSIGHTS.md](https://github.com/fieldsey/TTS-MPP-template/blob/master/INSIGHTS.md) file.

* Average bid
* Average winning bid
* Highest bid
* Lowest bid
* Total bids
* Total unique contractors
* Total unique contractors that are small businesses
* Average number of bids per user story
* Average number of days Issues are open
* Total number of questions received
* Average number of questions per user story
* Average internal PALT (from submission of the user story to award)
* Average official PALT (from posting the Issue to award)
* Average post-award PALT (from award to approval of payment)
* Total subscribers to mailing list

### User-story metrics
This data will be reported to the public in the [award information](https://github.com/fieldsey/TTS-MPP-template/tree/master/yyyy-mm-dd%20User-Story#award-information) section of an awarded user story’s `[README.md](https://github.com/fieldsey/TTS-MPP-template/blob/master/yyyy-mm-dd%20User-Story/README.md)` file.

* Winning bid
* Business size of the winning contractor
* Average bid
* Highest bid
* Lowest bid
* Total bids
* Total days Issue was open
* Total number of questions received
* Internal PALT
* Official PALT
* Post-award PALT

## Credits
### Acknowledgements
* [Jon Prisby](https://www.linkedin.com/in/jon-prisby/) for inspiring this idea.
* [Juan Quinones](https://www.linkedin.com/in/juan-quinones-3ab809103/) and Mark Junta for answering questions about how the Department of Veterans Affairs does this.
* [Ashley Owens](https://www.linkedin.com/in/ashley-owens-6996b175/), [Mark Hopson](https://www.linkedin.com/in/markchristopherhopson/), [Michelle McNellis](https://www.linkedin.com/in/michelle-mcnellis-9488908/), and [Omid Ghaffari-Tabrizi](https://www.linkedin.com/in/oghaffari/) (in order by first name) for answering questions about how TTS could do this and providing feedback on the first prototype.
* [David Jones](https://www.linkedin.com/in/devoops/) for being my first “user” and providing feedback from the perspective of a product owner.
* [Bret Mogilefsky](https://www.linkedin.com/in/bretmogilefsky/) for providing a great deal of feedback and for teaching me lessons learned from cloud.gov’s attempts at doing something similar.
* [Brent Maravilla](https://www.linkedin.com/in/brentmar/) for giving me useful feedback of what USDS is doing at their partner agencies.
