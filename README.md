Installation
============
Repo
----
Add the repo below in the usual way via the _File Manager_ and install
`repository.foxystreams-X.X.X.zip`. Do not use the `-dev` repo as it is almost
guaranteed to contain broken code.

    https://ruinernin.github.io/kodi


Config
======
General
-------
### Debrid Provider
After install choose a Debrid provider from settings.

#### RealDebrid
Simply choose RealDebrid and the OAuth device code to enter on
https://real-debrid.com/device will appear on the launch.

#### Premiumize
Select Premiumize as the provider and enter a valid API Key.

### Scraper
It is recommended to leave this as 'TorrentApi' by default and use 'BitLord' as
a backup via an external player.

### Reset auth
This will clear any saved login details for the current provider. _(Note: this
means the currently saved provider, not selected)_

### Show cached only
Set this to only show cached items, removing the ability to add magnets to the
Debrid provider.

Search categories
-----------------
Choose categories to search within on TorrentApi. In general switches here
should be set based on the desired quality.

Definition of ranked switch from [API](https://torrentapi.org/apidocs_v2.txt):

> By default the api will return only ranked torrents ( internal ) , scene
> releases + -rarbg releases + -rartv releases.
>
> If you want other groups included in the results use the ranked parameter with
> a value of 0 to get them included.


Usage
=====
Throughout green color text indicates a cached item and red indicates a
non-cached item. Selecting a non-cached item adds it to the Debrid provider.

OpenMeta
--------
Supports usage via OpenMeta. Player JSON is in the default repo.

Downloads
---------
Lists downloads from Debrid provider.

List
----
Lists latest 100 items for selected category switches.

Search
------
Lists search results for user inputted string in selected category switches.
