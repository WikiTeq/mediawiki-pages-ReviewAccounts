# mediawiki-pages-ReviewAccounts
A tool to review accounts based on the userpage properties.

# Requirements
* PageForms
* SemanticMediaWiki
* PageExchange or PagePort

# Setup

## via PagePort
* Download the repository
* Run php extensions/PagePort/maintenance/importPages.php --source ~/mediawiki-pages-ReviewAccounts

## via PageExchange
* Add the following line to your LocalSettings.php `$wgPageExchangePackageFiles[] = 'https://raw.githubusercontent.com/WikiTeq/mediawiki-pages-ReviewAccounts/master/page-exchange.json';`
* Navigate to Special:Packages and install the package
