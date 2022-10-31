# arasExploreDatamodel

This project proposes to add to the itemtype itself a tree grid view and query definition allowing admin users to navigate the full custom datamodel or the modification of existing OOTB objects.

As a administrator, consultant,... I often need to share the physical datamodel implemented in Aras.

This projects allow you to easily navigate, take screenshots to exchange on it.

Example on a custom item :
![Example on a custom item](./Screenshots/9%20Explore%20your%20Item%20datamodel.jpg)

Example on an OOTB item Part :
![Example on an OOTB item Part](./Screenshots/10%20Explore%20OOTB%20datamodel%20you%20modified.jpg)


## Project Details

Release | Notes
--------|--------
[V1](https://github.com/hguid/arasExploreDatamodel/tree/V1) | Enter your release notes here.

#### Supported Aras Versions

Project | Aras
--------|------
[V1](https://github.com/hguid/arasExploreDatamodel/tree/V1) | List the Aras versions supported by your project here. Ex: "11 SP12" or "11 SP10+"


## Installation

#### Important!
**Always back up your code tree and database before applying an import package or code tree patch!**

### Pre-requisites

1. Aras Innovator installed (version 11sp15 or > 12sp0 preferred)
2. Aras Package Import Utility
3. arasExploreDatamodel package stored in \arasExploreDatamodel\import

### Install Steps

TODO: Describe the installation process

1. launch the Import Utility
2. Connect to your server, database as admin
3. Select the path to the package to import
4. Select the arasExploreDatamodel package in the "Available for Import" list
5. Use Merge type and Thorough Mode options
6. Open your Aras and the search for the Tree Grid View arasExploreDatamodel
7. In the Actions menu select Set Usage and follow the popup menu actions


## Usage

TODO: Write usage instructions

1. In administration/itemtype, open any itemtype and search for the Explore Datamodel in the relationshiptab
2. You can navigate through your datamodel


## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request

(you can also use gitkraken... to do it without command line ;) )

## Credits
Hadrien Guiducci


## License
This project is published to Github under the MIT license. See the [LICENSE file](./LICENSE.md) for license rights and limitations.