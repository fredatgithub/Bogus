New Features
------------
Bogus a superset of **faker.js**'s features. Adding additional features are welcome. New features and additional APIs can be added so long as we maintain semantic API compatibility with **faker.js** and maintain compatibility with **faker.js** locale data.

Contributing
------------
Here are some helpful guidelines to keep in mind when contributing.  While following them isn't absolutely required, it does help everyone to accept your pull-requests with maximum awesomeness.

* :heavy_check_mark: **CONSIDER** adding a unit test if your PR resolves an issue or adds features.
* :heavy_check_mark: **DO** add XML comment documentation to new API calls along parameter documentation.
* :heavy_check_mark: **DO** reference any GH issues in the PR description.
* :heavy_check_mark: **DO** keep pull requests small so they can be easily reviewed. 
* :heavy_check_mark: **DO** keep the PR/change-set strictly focused on a specific change and on topic (ie: don't include code re-formatting). If you'd like to change something else off-topic, feel free to set up a new GH issue or PR for those off-topic changes.
* :heavy_check_mark: **DO** make sure unit tests pass.
* :x: **AVOID** changing existing code formatting (spaces, braces, tabs, new lines).
* :x: **AVOID** breaking the continuous integration build. 
* :x: **AVOID** Breaking compatibility with **faker.js** locale data.
* :x: **AVOID** Adding new locales to Bogus. New locales should be added upstream to **faker.js**. [See this wiki page for creating locales](https://github.com/bchavez/Bogus/wiki/Creating-Locales).