# PMC Governance

* [Overview](#overview)
* [Code of conduct](#code-of-conduct)
* [Roles and responsibilities](#roles-and-responsibilities)
  * [Users](#users)
  * [Contributors](#contributors)
  * [Committers](#committers)
  * [Project management committee](#project-management-committee)
    * [PMC Membership](#pmc-membership)
    * [PMC Meetings](#pmc-meetings)
* [Support](#support)
* [Contribution process](#contribution-process)
* [Decision making process](#decision-making-process)
  * [Lazy consensus](#lazy-consensus)
  * [Voting](#voting)
  * [Types of approval](#types-of-approval)
  * [When is a vote required?](#when-is-a-vote-required)
* [Conclusion](#conclusion)
* [Revision and Amendments](#revision-and-amendments)
* [Attribution](#attribution)

## <a name="overview"></a>Overview

This is a meritocratic, consensus-based community project. Anyone with an interest in the project can join the community, contribute to the project design and participate in the decision making process. This document describes how that participation takes place and how to set about earning merit within the project community.

## <a name="code-of-conduct"></a>Code of conduct

This community project aims to be an open and welcoming environment experience for everyone. All community members must follow this [code of conduct](https://github.com/odk-x/governance/blob/master/CODE-OF-CONDUCT.md).

## <a name="roles-and-responsibilities"></a>Roles and responsibilities

### <a name="users"></a>Users

Users are community members who have a need for the project. They are the most important members of the community and without them the project would have no purpose. Anyone can be a user; there are no special requirements.

The project asks its users to participate in the project and community as much as possible. User contributions enable the project team (Contributors, Committers, PMC) to ensure that they are satisfying the needs of those users. Common user contributions include (but are not limited to):

*   evangelizing about the project (e.g. a link on a website and word-of-mouth awareness raising)
*   informing developers of strengths and weaknesses from a new user perspective
*   providing moral support (a ‘thank you’ goes a long way)
*   providing financial support (the software is open-source, but its developers need to eat)

Users who continue to engage with the project and its community will often become more and more involved. Such users may find themselves becoming contributors, as described in the next section.

### <a name="contributors"></a>Contributors

Contributors are community members who contribute in concrete ways to the project. Anyone can become a contributor and contributions can take many forms. There is no expectation of commitment to the project, no specific skill requirements and no selection process.

In addition to their actions as users, contributors may also find themselves doing one or more of the following:

*   supporting new users (existing users are often the best people to support new users)
*   reporting bugs
*   identifying requirements
*   providing graphics and web design
*   programming
*   assisting with project infrastructure
*   writing documentation
*   fixing bugs
*   adding features

Contributors engage with the project through the issue trackers and mailing lists, or by writing or editing documentation. They submit changes to the project itself via patches, which will be considered for inclusion in the project by existing committers (see next section). The [ODK-X Forum Development Category](https://forum.odk-x.org/c/development) is the most appropriate place to ask for help when making that first contribution.

As contributors gain experience and familiarity with the project, their profile within, and commitment to, the community will increase. At some stage, they may find themselves being nominated for committership.

### <a name="committers"></a>Committers

Committers are community members who have shown that they are committed to the continued development of the project through ongoing engagement with the community. Committership allows contributors to more easily carry on with their project related activities by giving them direct access to the project’s resources. 

Seeking approval after making a contribution is known as a commit-then-review process. It is more efficient to allow trusted people to make direct contributions, as the majority of those contributions will be accepted by the project. The project employs various communication mechanisms to ensure that all contributions are reviewed by the community as a whole. By the time a contributor is invited to become a committer, they will have become familiar with the project’s various tools as a user and then as a contributor.

Anyone can become a committer; there are no special requirements, other than to have shown a willingness and ability to participate in the project as a team player. Typically, a potential committer will need to show that they have an understanding of the project, its objectives and its strategy. They will also have provided valuable contributions to the project over a period of time. New committers can be nominated by any existing committer. Once they have been nominated, there will be a vote by the project management committee (PMC; see below). Committer voting is one of the few activities that takes place on the project’s private management list. This is to allow PMC members to freely express their opinions about a nominee without causing embarrassment. The nominee is entitled to request an explanation of any ‘no’ votes against them, regardless of the outcome of the vote. This explanation will be provided by the PMC Chair (see below) and will be anonymous and constructive in nature.

Nominees may decline their appointment as a committer. However, this is unusual, as the project does not expect any specific time or resource commitment from its community members. The intention behind the role of committer is to allow people to contribute to the project more easily, not to tie them in to the project in any formal way.

*Note: If you make a significant contribution and are not considered for commit/write access on the appropriate resource, file an issue, post on the forum, or contact a PMC member directly and it will be brought up in the next PMC meeting.*

Modifications of project resources are made on a collaborative basis. Anybody may file an issue or propose a modification and it will be considered by project Committers. All changes must be reviewed and accepted by a Committer with sufficient expertise who is able to take full responsibility for the change.

In the case of changes proposed by an existing Committer, an additional Committer is required for review. Consensus should be sought if additional Committers participate and there is disagreement around a particular modification.

Committers may opt to elevate significant or controversial modifications or modifications that have not found consensus to the PMC for discussion by assigning the pmc-agenda tag to a pull request or issue or forum post. The PMC will serve as the final arbiter where required.

It is important to recognise that commitership is a privilege, not a right. That privilege must be earned and once earned it can be removed by the PMC (see next section) in extreme circumstances. However, under normal circumstances committership exists for as long as the committer wishes to continue engaging with the project.

### <a name="project-management-committee"></a>Project management committee

The project management committee (PMC) consists of those individuals identified as ‘organization owners’ of the GitHub organization. The PMC has additional responsibilities over and above those of a committer. These responsibilities ensure the smooth running of the project. PMC members’ duties generally include: 

*    Participate in strategic planning, 
*    Approve changes to the governance model
*    Manage the copyrights within the project outputs. 
*    Determine project roadmap (feature addition/removal, tool addition/removal, incorporating community feedback, etc.)
*    Setting high level technical direction
*    Forming appropriate suite Working Groups (e.g., User Feedback, Documentation, Translation) to gather the necessary community feedback before making decisions
*    Manage the project’s resources (e.g., code repositories, servers)
*    Maintaining the list of the suite's Committers

Members of the PMC do not have significant authority over other members of the community, although it is the PMC that votes on new committers. It also makes decisions when community consensus cannot be reached. Membership of the PMC is by invitation from the existing PMC members. A nomination will result in discussion and then a vote by the existing PMC members. PMC membership votes are subject to consensus approval of the current PMC members.

The PMC Chair is a single individual, voted for by the PMC members. The term length for the CMC chair is 1-year. Once someone has been appointed Chair, they remain in that role until they choose to retire, or the PMC casts a two-thirds majority vote to remove them.

The PMC Chair has no additional authority over other members of the PMC: the role is one of coordinator and facilitator. The Chair is also expected to ensure that all governance processes are adhered to, and has the casting vote when the project fails to reach consensus.

#### <a name="pmc-membership"></a>PMC Membership
The initial PMC membership will be seeded by existing members of Open Data Kit Technical Steering Committees. Appointment will happen when the “Open Data Kit PMC” establishes the new Project governance as part of the transition the motion will appoint members of the PMC based on “Open Data Kit TSC” membership at the time of the vote. The initial PMC term length will be 1 year.

After the initial selection at the time of Open Data Kit transition new members will be elected by a 2/3rds (rounded up) majority of the current PMC and serve for a term of 2 years, unless they resign or are removed. The PMC will use a public application process to give the community a chance to comment on the PMC applicants and ask questions of them applicants. The application requirements will focus on relevant experience, contributions to the project ecosystem, and availability to provide technical direction to the suite. Contributions to the project ecosystem should be considered with a broad definition that includes non-technical contributions to the community.

The PMC must have at least three members, but there is no fixed size. The expected target is between 6 and 12, from a minimum of 3 separate organizations, to ensure long-term sustainability, adequate coverage of important areas of expertise, and ability to make decisions efficiently.
There is no specific set of requirements or qualifications for PMC membership beyond these rules. That said, the likely best candidates for PMC membership will be Committers.

The PMC may add additional members by a PMC motion. A PMC member may be removed by voluntary resignation, or by a 2/3rds majority (rounded up).
PMC members are expected to regularly participate in PMC activities. Members who have not consistently taken meaningful actions as PMC members in the past 3 months will be considered for removal. Examples of meaningful actions are participating regularly in calls, reviewing code, committing code, providing technical mentorship, leading working groups, etc.

No more than 1/3 of the PMC members may be affiliated with the same organization. If removal or resignation of a PMC member, or a change of employment by a PMC member, creates a situation where more than 1/2 of PMC membership belong to the same organization, the situation must be immediately remedied by the resignation or removal of one or more PMC members affiliated with the over-represented organization(s).

Changes to PMC membership should be posted in the agenda, and may be suggested as any other agenda item.

#### <a name="pmc-meetings"></a>PMC Meetings
The PMC will meet regularly (generally every two weeks). The meeting will be run by a moderator chosen by the PMC and each meeting will be conducted and published to a publicly accessible platform (e.g., UberConference). Meeting frequency, times, agenda, and notes will also be published to a publicly accessible platform (e.g., the forum, Google Docs).

The PMC will default to working in public, but sensitive topics (e.g., pre-disclosure security problems, confidential pre-agreement discussions with third parties, personal conflicts among personnel) should only be discussed on private channels.

Items typically discussed by the PMC include suite roadmap, feature addition/removal, etc. Items are added to the PMC agenda which are considered contentious or are modifications of governance, contribution policy, PMC membership, or release process. Working Groups that the PMC forms may also add items to the PMC agenda.
The intention of the agenda is not to approve or review modifications to suite resources. That should happen continuously on the relevant resources and are handled by the larger group of Committers.

Any community member or contributor can ask that something be added to the next meeting's agenda by filing an issue or writing a forum post. Any Committer or forum moderator can add the item to the agenda by adding the pmc-agenda tag to the issue or post.

Prior to each PMC meeting, the moderator will share the agenda with members of the PMC. PMC members can add any items they like to the agenda at the beginning of each meeting. The moderator and the PMC cannot veto or remove items.

The PMC may invite non-members to participate in a non-voting capacity. These invitees will be listed on the agenda.

The moderator is responsible for summarizing the discussion of each agenda item and publishing it on a publicly accessible platform (e.g., the forum). If appropriate, the moderator will also update the relevant issue, pull request or forum post.

## <a name="support"></a>Support

All participants in the community are encouraged to provide support for new users within the project management infrastructure. This support is provided as a way of growing the community. Those seeking support should recognise that all support activity within the project is voluntary and is therefore provided as and when time allows. A user requiring guaranteed response times or results should therefore seek to purchase a support contract from a community member. However, for those willing to engage with the project on its own terms, and willing to help support other users, the community support channels are ideal.

## <a name="contribution-process"></a>Contribution process

Anyone can contribute to the project, regardless of their skills, as there are many ways to contribute. For instance, a contributor might be active on the forum and issue trackers, or might supply patches.

Contributors can also help by providing feedback helping new users recommending the project to others, testing and reporting or fixing bugs, requesting new features, writing and updating software, creating artwork, writing or updating documentation, and translating.

The [ODK-X Forum Development Category](https://forum.odk-x.org/c/development) is the most appropriate place for a contributor to ask for help when making their first contribution.

## <a name="decision-making-process"></a>Decision making process
Decisions about the future of the project are made through discussion with all members of the community, from the newest user to the most experienced PMC member. All non-sensitive project management discussion takes place on project discussion forums. Occasionally, sensitive discussion occurs on a private list.

In order to ensure that the project is not bogged down by endless discussion and continual voting, the project operates a policy of lazy consensus. This allows the majority of decisions to be made without resorting to a formal vote.

### <a name="lazy-consensus"></a>Lazy consensus

Decision making typically involves the following steps:

*   Proposal
*   Discussion
*   Vote (if consensus is not reached through discussion)
*   Decision

Any community member can make a proposal for consideration by the community. In order to initiate a discussion about a new idea, they should send an email to the project contributors’ list or submit a patch implementing the idea to the issue trackers (or version-control system if they have commit access). This will prompt a review and, if necessary, a discussion of the idea. The goal of this review and discussion is to gain approval for the contribution. Since most people in the project community have a shared vision, there is often little need for discussion in order to reach consensus.

In general, as long as nobody explicitly opposes a proposal or patch, it is recognised as having the support of the community. This is called lazy consensus - that is, those who have not stated their opinion explicitly have implicitly agreed to the implementation of the proposal.

Lazy consensus is a very important concept within the project. It is this process that allows a large group of people to efficiently reach consensus, as someone with no objections to a proposal need not spend time stating their position, and others need not spend time reading such mails.

For lazy consensus to be effective, it is necessary to allow at least 72 hours before assuming that there are no objections to the proposal. This requirement ensures that everyone is given enough time to read, digest and respond to the proposal. This time period is chosen so as to be as inclusive as possible of all participants, regardless of their location and time commitments.


### <a name="voting"></a>Voting

Not all decisions can be made using lazy consensus. Issues such as those affecting the strategic direction or legal standing of the project must gain explicit approval in the form of a vote. If a formal vote on a proposal is called (signaled simply by sending a email with ‘[VOTE]’ in the subject line). They do this by sending an email in reply to the original ‘[VOTE]’ email, with the following vote and information:

*    +1 ‘yes’, ‘agree’: also willing to help bring about the proposed action
*    +0 ‘yes’, ‘agree’: not willing or able to help bring about the proposed action
*    -0 ‘no’, ‘disagree’: but will not oppose the action’s going forward
*    -1 ‘no’, ‘disagree’: opposes the action’s going forward and must propose an alternative action to address the issue (or a justification for not addressing the issue)
*    ‘Veto:’ which means the PMC member rejects the voting method as the member believes that the issue is such an important one that it requires Consensus approval or Unanimous consensus instead. Vetos themselves can be overruled by ⅔ majority of the PMC.

To abstain from the vote, participants simply do not respond to the email. However, it can be more helpful to cast a ‘+0’ or ‘-0’ than to abstain, since this allows the team to gauge the general 

Depending on the type of vote (e.g. Consensus approval, Unanimous consensus)   ‘-1’ can end a proposal since they already require no ‘-1’ votes. In other cases (e.g.,Lazy consensus) a -1 would simply indicate an objection, however, a PMC member can make a binding ‘veto’ that prevents it from moving forward until an appropriate voting method is used. A PMC member using a ‘veto’ should believe that the issue is such an important one that it requires Consensus approval or Unanimous consensus instead. Vetos themselves can be overruled by ⅔ majority of the PMC if the other PMC members do not believe that the issue is significant and that the ‘veto’ is being abused.

When a [VOTE] receives a ‘-1’, it is the responsibility of the community as a whole to address the objection. Such discussion will continue until the objection is either rescinded, overruled by the majority of voters explaining why they think the objection should not hold up the proposal, or the proposal itself is altered in order to achieve consensus (possibly by withdrawing it altogether). 

In summary:
*    Those who don’t agree with the proposal and think they have a better idea should vote -1 and defend their counter-proposal.
*    Those who don’t agree but don’t have a better idea should vote -0.
*    Those who agree but will not actively assist in implementing the proposal should vote +0.
*    Those who agree and will actively assist in implementing the proposal should vote +1.

### <a name="types-of-approval"></a>Types of approval

Different actions require different types of approval, ranging from lazy consensus to a majority decision by the PMC. These are summarised in the table below. The section after the table describes which type of approval should be used in common situations.

<table>
    <thead>
        <tr>
            <th>Type</th>
            <th>Description</th>
            <th>Duration</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Lazy consensus</td>
            <td>An action with lazy consensus is implicitly allowed, unless a binding -1 vote is received. Depending on the type of action, a vote will then be called. Note that even though a binding -1 is required to prevent the action, all community members are encouraged to cast a -1 vote with supporting argument. PMC are expected to evaluate the argument and, if necessary, support it with a ‘veto’ that the decision has too many implications for Lazy consensus.</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td>Lazy majority</td>
            <td>A lazy majority vote requires more binding +1 votes than binding -1 votes.</td>
            <td>72 hours</td>
        </tr>
        <tr>
            <td>Consensus approval</td>
            <td>Consensus approval requires three binding +1 votes and no binding -1 votes.</td>
            <td>72 hours</td>
        </tr>
        <tr>
            <td>Unanimous consensus</td>
            <td>All of the binding votes that are cast are to be +1 and there can be no binding vetoes (-1).</td>
            <td>120 hours</td>
        </tr>
        <tr>
            <td>2/3 majority</td>
            <td>Some strategic actions require a 2/3 majority of PMC members; in addition, 2/3 of the PMC votes cast must be +1. Such actions typically affect the foundation of the project (e.g. adopting a new codebase to replace an existing product).</td>
            <td>120 hours</td>
        </tr>
    </tbody>
</table>

### <a name="when-is-a-vote-required"></a>When is a vote required?

Every effort is made to allow the majority of decisions to be taken through lazy consensus. That is, simply stating one’s intentions is assumed to be enough to proceed, unless an objection is raised. However, some activities require a more formal approval process in order to ensure fully transparent decision making. The table below describes some of the actions that will require a vote. It also identifies which type of vote should be called.

<table>
    <thead>
        <tr>
            <th>Action</th>
            <th>Description</th>
            <th>Approval type</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Release plan</td>
            <td>Defines the timetable and actions for a release. A release plan cannot be vetoed (hence lazy majority).</td>
            <td>Lazy majority</td>
        </tr>
        <tr>
            <td>Product release</td>
            <td>When a release of one of the project’s products is ready, a vote is required to accept the release as an official release of the project. A release cannot be vetoed (hence lazy majority).</td>
            <td>Lazy majority</td>
        </tr>
        <tr>
            <td>New committer</td>
            <td>A new committer has been proposed.</td>
            <td>Consensus approval of the PMC</td>
        </tr>
        <tr>
            <td>Committer removal</td>
            <td>When removal of commit privileges is sought.</td>
            <td>Unanimous consensus of the PMC</td>
        </tr>
        <tr>
            <td>Governance Document Changes</td>
            <td>Changes to the governance, copyrights, or other major decisions affecting the project.</td>
            <td>Unanimous consensus of the PMC</td>
        </tr>
        <tr>
            <td>PMC member removal</td>
            <td>When removal of PMC membership is sought.</td>
            <td>2/3 majority</td>
        </tr>
    </tbody>
</table>

## <a name="conclusion"></a>Conclusion

A clear and transparent governance document is a key part of any open development project. It defines the rules of engagement within the community and describes what level of influence a community member can expect to have over a project. In addition, it enables members to decide their level of involvement with that community. In the case of a meritocracy, it also provides a clear way to contribute and a highly visible reward system.

All that said, please remember that this project is your project. The point of this document is to grow the project by enabling, facilitating, and securing contributions in a manner that satisfies everyone. Pull requests and comments about the documents are always welcome, either here in the repository or in our community forums.


## <a name="revision-and-amendments"></a>Revision and Amendments

This document is owned by the PMC and amendments may only be made by decisions of the PMC.

## <a name="attribution"></a>Attribution

This a derivative work of the [Meritocratic Governance Model](http://oss-watch.ac.uk/resources/meritocraticgovernancemodel), [Node.js Project Governance](https://raw.githubusercontent.com/nodejs/nodejs.org/0dd684cf21d278ba8aa178db0a20ebc6d587c58e/locale/en/about/governance.md). [Meritocratic Governance Model](http://oss-watch.ac.uk/resources/meritocraticgovernancemodel) is licensed under the [Attribution-ShareAlike 4.0 International](https://creativecommons.org/licenses/by-sa/4.0/) license with copyright held by Ross Gardler and Gabriel Hanganu. [Node.js Project Governance](https://raw.githubusercontent.com/nodejs/nodejs.org/0dd684cf21d278ba8aa178db0a20ebc6d587c58e/locale/en/about/governance.md) is licensed under the [MIT](https://opensource.org/licenses/MIT) license with copyright held by Node.js Website WG contributors.

