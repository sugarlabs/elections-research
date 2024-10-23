# elections-research
Research of different elections software

## Election software researched

*A list of various election software recommended to us that we've researched*

* [https://electionbuddy.com/](https://electionbuddy.com/)  
* [https://elekto.dev/](https://elekto.dev/)  
  * Preference method voting  
  * [https://github.com/elekto-io/elekto](https://github.com/elekto-io/elekto)  
* [https://github.com/cncf/gitvote](https://github.com/cncf/gitvote)  
* [https://star.vote/](https://star.vote/)  
  * [https://dev.star.vote/](https://dev.star.vote/)  
  * [https://equal-vote.github.io/star-server/](https://equal-vote.github.io/star-server/)  
* [https://openslides.com/en](https://openslides.com/en)  
* [https://steve.apache.org/](https://steve.apache.org/)  
* [https://www.belenios.org/](https://www.belenios.org/)  
* [https://civs1.civs.us/](https://civs1.civs.us/)

## Comparison of election software

*A comparison of election software recommended to us based on the
 criteria of voting type, license, hosting, and anonymity, along with
 some preliminary conclusions based on our needs at Sugar Labs.*

|  | Election Buddy | Elekto | Git Vote | Star Vote | Open Slides | Apache | Belenios | Civs1 |
| :---- | :---- | :---- | :---- | :---- | :---- | :---- | :---- | :---- |
| Website: | [https://electionbuddy.com/](https://electionbuddy.com/) [https://electionbuddy.com/process/ballot-samples/executive-elections/](https://electionbuddy.com/process/ballot-samples/executive-elections/)  | [https://elekto.dev/](https://elekto.dev/) https://github.com/elekto-io/elekto/tree/main | https://github.com/cncf/gitvote | [https://star.vote/](https://star.vote/) Beta: [https://dev.star.vote/](https://dev.star.vote/) 10/23/24 update: dev.star forwards to [https://bettervoting.com/](https://bettervoting.com/)  | [https://openslides.com/en](https://openslides.com/en) https://github.com/OpenSlides/OpenSlides | [https://steve.apache.org/](https://steve.apache.org/)  | [https://www.belenios.org/index.html](https://www.belenios.org/index.html) [https://www.belenios.org/software.html](https://www.belenios.org/software.html) https://vote.belenios.org/admin | [https://civs1.civs.us/](https://civs1.civs.us/) https://github.com/andrewcmyers/civs |
| Voting type(s): | Plurality, ranked-choice voting, approval voting | Preference method voting | Seems like just a simple check? | Automatic runoff; development “will ranked ballots, simple "approval" (choose-any) ballots, or STAR Voting.” | Cumulative and run-off. https://openslides.com/en/elections/ |  | Not entirely clear from the website [https://www.belenios.org/howitworks.html](https://www.belenios.org/howitworks.html) https://www.belenios.org/faq.html | Ranked choice |
| License: | ??? https://electionbuddy.com/terms-of-service/ | Apache 2.0 | Apache 2.0 | AGPLv3 | MIT license | (404 on software page) | AGPLv3 | MIT |
| Anonymous? | [https://electionbuddy.com/features/](https://electionbuddy.com/features/) “All voting choices are confidential and cannot be linked to the voter for elections. And results can be hidden until the election ends for further anonymity.” | It seems so. [https://elekto.dev/docs/overview/goals/](https://elekto.dev/docs/overview/goals/) (no email?) | I can’t imagine that this could ever be  | ?? (To be researched) | Unsure |  | “no one can learn the vote of a voter. Vote privacy relies on the encryption of the votes.” Seems to be by email / login | Seems to be. See: https://civs1.civs.us/sec\_priv.html |
| Hosting | Cloud-based only, it seems | Self hosted only? | Github | Self hosted and on their site. There is free and professional, but the professional may be free for nonprofits. | Self and on their site |  | Self-hosted and account on their website (https://vote.belenios.org/admin) | Self-hosted and it seems you can use on their site: [https://civs1.civs.us/civs\_create.html](https://civs1.civs.us/civs_create.html) and https://civs1.civs.us/cgi-bin/opt\_in.pl |
| Used by: | Freedesktop Union (Molly DeBlanc) | Kubernetes community | “won't be helpful for your type of elections but could be useful for public project decisions” |  | “Quite popular in Germany” | Apache foundation |  | ?? |
| Notes |  | “It's very single purpose for their needs but could work for others if they wanted to invest in helping out: https://github.com/elekto-io/elekto” |  | “\[T\]he team behind it is currently working on a name change because the software has been expanded to support multiple voting methods. It will support ranked ballots, simple "approval" (choose-any) ballots, or STAR Voting.” |  |  | “It has been used in thousands of elections” |  |
| Recommend? And why? | No. Prefer not as doesn’t seem to be FOSS | Yes. Worth looking into, but may be something we need to host. | No. | Yes. This is worth looking into, and it seems we can use their dev page as the host. | No. It’s not clear what voting types they have. The documentation seems muddled and is not all translated to English. | No. Not until I can get more info. | No. There doesn’t seem to be ranked or approval methods | Maybe. It doesn’t seem well maintained and only has ranked choice..  |