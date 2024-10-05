# Contributing to eIDAS2.0 Wallets

> This is still a work in progress, in this phase we are open for feedback and suggestions about our format. 
>
> To get into contact visit the maintainers website and find the contact information, got to minimize the spam :)

## Formatting

Current eIDAS Wallet entry format:

Name | Description | Available | Planned for | Pricing | Key Features 
|:---|:---|:---|:---|:---|:---|
| Wallet Name(Link to Wallet) | Description of Wallet * | Is the Wallet available now? | Date of presumed availability | Free or Commercial | Bulleted list of Key Features * |

Example entry:

```
| [NL ID-wallet](https://digitaleoverheid.nl/overzicht-van-alle-onderwerpen/identiteit/id-wallet/) | Easily share your personal data safely. In the Netherlands and the EU | No | Q2 2025 | Free | - Backed by NL Government <br> - Verify personal details |
```

\* Descriptions will only be accepted when:

* Does not contain URL's
* Maximum of 14 words

\* Key Features will only be accepted when:

* Features does not contain an URL
* Maximum of 3 Key Features


After you've created a branch on your fork with your changes, it's time to [make a pull request][pr-link]. 


*Please follow the guidelines given below while making a Pull Request to the eIDAS2.0 Wallets*

## Pull Request Guidelines

* Continue to follow the alphabetical ordering that is in place per section.
* Each table column should be padded with one space on either side.
* The Description should not exceed 14 words.
* Add one link per Pull Request.
* Make sure the PR title is in the format of `Add Wallet` *for e.g.*: `Add FastID`
* Use a short descriptive commit message. *for e.g.*: ❌`Update Readme.md`  ✔ `Add FastID to Wallet listing`
* Search previous Pull Requests or Issues before making a new one, as yours may be a duplicate.
* Don't mention the TLD(Top Level Domain) in the name of the Wallet. *for e.g.*: ❌Gmail.com ✔Gmail
* Target your Pull Request to the `main` branch of the `eidas2-wallets

Once you’ve submitted a pull request, the collaborators can review your proposed changes and decide whether or not to incorporate (pull in) your changes.

### Pull Request Pro Tips

* [Fork][fork-link] the repository and [clone][clone-link] it locally.
Connect your local repository to the original `upstream` repository by adding it as a [remote][remote-link].
Pull in changes from `upstream` often so that you stay up to date and so when you submit your pull request,
merge conflicts will be less likely. See more detailed instructions [here][syncing-link].
* Create a [branch][branch-link] for your edits.
* Contribute in the style of the project as outlined above. This makes it easier for the collaborators to merge
and for others to understand and maintain in the future.

### Open Pull Requests

Once you’ve opened a pull request, a discussion will start around your proposed changes.

Other contributors and users may chime in, but ultimately the decision is made by the collaborators.

During the discussion, you may be asked to make some changes to your pull request.

If so, add more commits to your branch and push them – they will automatically go into the existing pull request. But don't forget to squash them.

*Special Thanks to `public-apis` for starting a great example of project listings!*

[branch-link]: <http://guides.github.com/introduction/flow/>
[clone-link]: <https://help.github.com/articles/cloning-a-repository/>
[fork-link]: <http://guides.github.com/activities/forking/>
[oauth-link]: <https://en.wikipedia.org/wiki/OAuth>
[pr-link]: <https://help.github.com/articles/creating-a-pull-request/>
[remote-link]: <https://help.github.com/articles/configuring-a-remote-for-a-fork/>
[syncing-link]: <https://help.github.com/articles/syncing-a-fork>
[squash-link]: <https://github.com/todotxt/todo.txt-android/wiki/Squash-All-Commits-Related-to-a-Single-Issue-into-a-Single-Commit>