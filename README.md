# TransLatin overview

There are three repositories in
[GitHub/HuygensING](https://github.com/HuygensING)
that contain data produced by the Translatin project:

*   [translatin-wemi](https://github.com/HuygensING/translatin-wemi)
    Metadata preparation and analysis to identify works, expressions, manifestations
    and items (wemi), in the
    [FRBR sense](https://en.wikipedia.org/wiki/Functional_Requirements_for_Bibliographic_Records)

*   [translatin-manif](https://github.com/HuygensING/translatin-manif)
    Publication of a selection of manifestations, as
    [text-fabric](https://github.com/annotation/text-fabric) files, with an
    [annotation](https://annotation.github.io/text-fabric/tf/convert/watm.html) export
    to the publishing pipeline of TeamText of HuC-DI.

*   [translatin](https://github.com/HuygensING/translatin)
    Data production for the final published result of the project: a collection
    of 100+ medieval, latin dramas.

The most comprehensive information on Translatin, the project, the people involved,
the data and the programs, is in
[translatin-manif](https://github.com/HuygensING/translatin-manif).

## About this repo

This is work done by Hayco de Jong and Jirsi Reinders.

Jirsi has compiled extensive spreadsheets with metadata on medieval, latin plays, 
in order to group extant copies into expressions, and those into manifestations, and
those into works.

Hayco has modelled this data relationally and stored it in a Postgres Database.

In [translatin-manif](https://github.com/HuygensING/translatin-manif), Dirk
Roorda has used the contents of that database to mix metadata into a selection of 
manifestations which were published through a Text-Fabric pipeline.
