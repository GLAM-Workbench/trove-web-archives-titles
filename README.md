# trove-web-archives-titles

This dataset contains a complete list of Pandora's archived web resource titles.

These datasets were generated using notebooks in the [trove-web-archives](https://github.com/GLAM-Workbench/trove-web-archives/) repository.

For more information and documentation see the [Pandora titles data](https://glam-workbench.net/trove-web-archives/pandora-titles-data) section of the [GLAM Workbench](https://glam-workbench.net).

## Dataset summary
- [pandora-titles.csv](https://github.com/GLAM-Workbench/trove-web-archives-titles/raw/main/pandora-titles.csv) (13.2 MB, text/csv)


## Dataset details

### [pandora-titles.csv](https://github.com/GLAM-Workbench/trove-web-archives-titles/raw/main/pandora-titles.csv)

|                |                                                                                                                                                                                                                                                    |
|:---------------|:---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| date harvested | 2024-05-03                                                                                                                                                                                                                                         |
| file size      | 13.2 MB                                                                                                                                                                                                                                            |
| format         | text/csv                                                                                                                                                                                                                                           |
| created by     | <a href='https://github.com/GLAM-Workbench/trove-web-archives/blob/master/harvest-pandora-titles.ipynb'>Harvest the full collection of Pandora titles</a> ([documentation](https://glam-workbench.net/trove-web-archives/harvest-pandora-titles/)) |
| number of rows | 87742                                                                                                                                                                                                                                              |

#### Columns

| name           | type   | description                                                                                                                                                                                                         |
|:---------------|:-------|:--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `tep_id`       | string | Title Entry Page (TEP) identifier                                                                                                                                                                                   |
| `name`         | string | name of the archived resource                                                                                                                                                                                       |
| `gathered_url` | string | the original url of the archived resource                                                                                                                                                                           |
| `surt`         | string | the surt (Sort-friendly URI Reordering Transform) is a version of the url that reverses the order of the domain components to put the top-level domain first, making it easier to group or sort resources by domain |## Examples of use



----
Created by [Tim Sherratt](https://timsherratt.au) for the [GLAM Workbench](https://glam-workbench.net)