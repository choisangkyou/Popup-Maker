# Popup Maker
Everything you need to create unique popup user experiences. Insert forms & other content from your favorite plugins to create custom responsive popups.

Feel free to browse the code and make suggestions/requests. Thanks!

## Getting Started

### Downloading And Using As A Plugin
To use this plugin, you must download from [the releases page](https://github.com/PopupMaker/Popup-Maker/releases). With each release, there is an attached zip, named something similar to `popup-maker_v1.10.2.zip
`. Download the appropriate zip file and then upload into your WordPress site as a normal plugin. 

Once installed and activated, Go to wp-admin > Popup Maker > Add Popup to create your first popup.

### Getting Set Up For Development
In order to begin development on Popup Maker, please refer to our [Setting up your local environment](https://github.com/PopupMaker/Popup-Maker/wiki/Setting-up-your-local-environment) wiki page.

#### Gulp Tasks
As normal, we have our gulp tasks in the gulpfile.js file.

To build the css files, run `gulp css`.

To build the js files, run `gulp js`. 

## Built With
* [SASS](https://sass-lang.com) - The CSS pre-processor we use. We use the SCSS syntax.
* [jQuery](https://jquery.com) - A fast, small, and feature-rich JavaScript library
* [JSON for JS](https://github.com/douglascrockford/JSON-js) - Creates a JSON property in the global object, if there isn't already one
* [iFrame Resizer](https://github.com/davidjbradshaw/iframe-resizer) - Force cross domain iframes to size to content
* [mobile-detect.js](https://github.com/hgoebl/mobile-detect.js) - Detect the device by comparing patterns against a given User-Agent string

## Deployment
This is a WordPress plugin that is hosted on the WordPress.org SVN repo.
There is not currently any automated deployment. Instead, once a release is published on GitHub, that release is manually uploaded to the SVN.

## Contributing
Community made feature requests, patches, localizations, bug reports, and contributions are always welcome and are crucial to ensure Popup Maker continues to grow.

When contributing please ensure you follow the guidelines below so that we can keep on top of things.

Please Note: GitHub is not intended for support based questions. For those, please use the [support forums](https://wordpress.org/support/plugin/popup-maker/).

### Creating Issues
* If you have any bugs or feature requests, please [create an issue](https://github.com/PopupMaker/Popup-Maker/issues/new)
* For bug reports, please clearly describe the bug/issue and include steps on how to reproduce it
* For feature requests, please clearly describe what you would like, how it would be used, and example screenshots (if possible)

### Pull Requests
* Ensure you stick to the [WordPress Coding Standards](https://codex.wordpress.org/WordPress_Coding_Standards)
* When committing, reference your issue (if present) and include a note about the fix
* Push the changes to your fork and submit a pull request to the 'master' branch of this repository
* We are trying to ensure that every function is documented well and follows the standards set by phpDoc going forward

## Versioning
We use [SemVer](http://semver.org/) for versioning. For the versions available, see [the releases in this repository](https://github.com/PopupMaker/Popup-Maker/releases).

## Developers
* Daniel Iser - Lead Developer

See also [the list of contributors](https://github.com/PopupMaker/Popup-Maker/graphs/contributors) who participated in this project.

## License
This project is licensed under the GPLv2 License.

## Support
This is a developer's portal for Popup Maker and **should not** be used for support. Please [create a support ticket here](https://wordpress.org/support/plugin/popup-maker/).
