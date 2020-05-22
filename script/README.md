# Maintenance

To update `country.csv`:

1. Open <https://www.iso.org/obp/ui/#search/code/>
1. Open the *Network* tab of the *Web Inspector* (Option-Cmd-I) in Safari
1. Set *Results per page:* to 300
1. Click the last *UIDL* entry in the *Network* tab
1. Copy its contents, excluding the for-loop, into a file
1. Run:

        ./script/update path/to/file
