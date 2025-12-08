# lightroom-keyword-starter
Keyword starter for a landscape photographer.  Primarily focuses on location-based tags.

Lightroom keyword format
1. newline = new sibling tag item
2. newline with tab = subitem in menu
3. newline with tab and {} brackets = alternative name for the parent, included on export
4. item with [] brackets = not included on export, only used for organization

Feel free to send pull requests, will do my best to make this a good resource

Format requested

```
[WORLD LOCATION]
    Continent
        Country
            {Country with alternate spelling, native language spelling, or non-Latin Characters}
            City
                {City with alternate spelling or non-Latin Characters, example Vienna vs Wein}
                Landmark or Park
                    Feature at Above Landmark
                
```

Example

```
[WORLD LOCATION]
    Europe
        Iceland
            {Ísland}
            {Island}
            Austurland Region
                Jokulsarlon
                    {Jökulsárlón}
                    Jokulsarlon Beach
                        {Jökulsárlón Beach}
                        {Iceberg Graveyard}
```

When importing, as long as everything lines up, it _should_ import a new area into the existing tree.  Expect a few typos, it is a work in progress.