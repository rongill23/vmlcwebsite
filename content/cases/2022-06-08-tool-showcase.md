---
title: Tool Showcase
Draft: false
Categories: cases
Tags: virtual-server
Screenshots: /images/uploads/image.png
---
# This page is meant ot showcase the capabilites of this tool.

<hr>

# These are subsections which can easily organize content via the sidebar ->

## These are subsections which can easily organize content via the sidebar ->

### These are subsections which can easily organize content via the sidebar ->

### These are subsections which can easily organize content via the sidebar ->

#### These are subsections which can easily organize content via the sidebar ->

<hr>

# Cool features:

## Code Snippet -

```java
// this is java syntax

String hello = "Hello World";

System.out.println(hello);
```


## Treeview - 

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


## Intro

{{< intro
  introtitle="I'm an intro"
  id="introTest"
>}}
{
  "showBullets": false,
  "showStepNumbers": true,
  "onexit": "console.log(\"I'm exiting the intro\");",
  "oncomplete": "console.log(\"I'm exiting the intro after completing it\");",
  "steps": [
    {
      "title": "Step 1",
      "intro": "I'm step 1 for everyone",
      "onchange": "console.log(\"I'm entering step 1 for everyone\");"
    },{
      "title": "Step 2",
      "intro": "I'm step 2 for the desktop trigger",
      "onchange": "console.log(\"I'm entering step 2 for the desktop trigger\");",
      "triggeronly": ["desktop"]
    },{
      "title": "Step 2",
      "intro": "I'm step 2 for the mobile and touch triggers",
      "onchange": "console.log(\"I'm entering step 2 for the mobile and touch triggers\");",
      "triggeronly": ["mobile","touch"]
    },{
      "title": "Step 3",
      "intro": "I'm step 3 for everyone except the hover trigger",
      "onchange": "console.log(\"I'm entering step 3 for everyone except the hover trigger\");",
      "triggerexcept": ["hover"]
    },{
      "title": "Step 3",
      "intro": "I'm step 3 for everyone except the nohover trigger",
      "onchange": "console.log(\"I'm entering step 3 for everyone except the nohover trigger\");",
      "triggerexcept": ["nohover"]
    },{
      "title": "Step 4",
      "element": "#globalLogo",
      "intro": "I'm step 4 for everyone on the #globalLogo element",
      "onchange": "console.log(\"I'm entering step 4 for everyone on the #globalLogo element\");"
    },{
      "title": "Step 5",
      "element": "#globalLogo",
      "intro": "I'm step 5 for everyone on the #globalLogo element on right position",
      "position": "right",
      "onchange": "console.log(\"I'm entering step 5 for everyone on the #globalLogo element on right position\");"
    }]
}
{{< /intro >}}




