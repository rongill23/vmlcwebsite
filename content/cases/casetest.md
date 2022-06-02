---
title: "Casetest"
date: 2022-06-02T08:36:56-05:00
draft: false
---


# This is a Test Case for presentation.

1.Example
2.List



{{< treeview
    display="tree"
>}}
[{
    "kind": "dir",
    "label": "***Directory***",
    "content": [{
            "kind": "archive",
            "label": "***Archive***",
            "content": [{
                    "kind": "dir",
                    "label": "***Directory** in an archive*",
                    "content": [{
                            "kind": "file",
                            "label": "***Flat file** in a directory in an archive*"
                        }]
                },{
                    "kind": "file",
                    "label": "***Flat file** in an archive*"
                }]
        },{
            "kind": "file",
            "label": "***Flat file** in a directory*"
        }]
},{
    "kind": "default",
    "label": "***Default***"
},{
    "kind": "dir",
    "label": "***Directory***"
},{
    "kind": "file",
    "label": "***File***"
},{
    "kind": "home",
    "label": "***Home***"
},{
    "kind": "page",
    "label": "***Page***"
},{
    "kind": "section",
    "label": "***Section***"
},{
    "kind": "taxonomy",
    "label": "***Taxonomy***"
},{
    "kind": "term",
    "label": "***Taxonomy's term***"
},{
    "kind": "archive",
    "label": "***Archive***"
},{
    "kind": "image",
    "label": "***Image file***"
},{
    "kind": "video",
    "label": "***Video file***"
},{
    "kind": "script",
    "label": "***Script***"
},{
    "kind": "dockerfile",
    "label": "***Dockerfile***"
},{
    "kind": "pdf",
    "label": "***PDF file***"
},{
    "kind": "powerpoint",
    "label": "***PowerPoint file***"
},{
    "kind": "excel",
    "label": "***Excel file***"
},{
    "kind": "csv",
    "label": "***CSV file***"
},{
    "kind": "word",
    "label": "***Word file***"
}]
{{< /treeview >}}

