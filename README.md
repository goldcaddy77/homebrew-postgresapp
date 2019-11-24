# homebrew-postgresapp

## Summary

## Dependencies

It is assumed that [homebrew](http://brew.sh/) and [homebrew-cask](https://github.com/caskroom/homebrew-cask) have already been installed. If not refer to the quick start commands below (refer to the linked sites for further explanation).

### Install [brew]

    ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"

### Install [cask]

    brew install caskroom/cask/brew-cask

## Installing the Postgres.app casks

    brew tap goldcaddy77/homebrew-postgresapp
    brew cask install postgresapp-12

## Uninstalling the casks

    brew cask uninstall postgresapp

## Adding new versions

See [Adding New Versions]

## Auto updates

At present, these firefox installations will honour your existing preferences for firefox updates. So by default it
will try and update automatically. To stop this happening go to firefox preferences, select update tab and select
"Never check for updates".

[homebrew cask]: http://caskroom.io
[brew]: http://brew.sh/
[cask]: https://github.com/caskroom/homebrew-cask
[firefox]: https://www.mozilla.org/en-GB/firefox/new/
[cask header style]: https://github.com/caskroom/homebrew-cask/commit/25f7cfee04c1d0c470dd1e6b7eaff56fb2598172
[smclernon]: https://github.com/smclernon/homebrew-firefox
[adding new versions]: https://github.com/goldcaddy77/homebrew-firefox/wiki/Adding-New-Versions
