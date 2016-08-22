# TerminalFOUR naming style guide

version 0.5.2
Last updated: Monday 22 August 2016

The terms MUST, MUST NOT, SHOULD, SHOULD NOT, and MAY are used in this document with the meanings found in [RFC 2119: Key words for use in RFCs to indicate requirement levels](https://www.ietf.org/rfc/rfc2119.txt).

<!-- MarkdownTOC depth=4 -->

- [1. Introduction](#1-introduction)
- [2. T4 Assets](#2-t4-assets)
    - [2.1 Section names](#21-section-names)
    - [2.2 Page layouts](#22-page-layouts)
    - [2.3 Content types](#23-content-types)
        - [2.3.1 Content names](#231-content-names)
        - [2.3.2 Content type formatters](#232-content-type-formatters)
        - [2.3.3 Content type elements](#233-content-type-elements)
        - [2.5.4 List items](#254-list-items)
        - [2.3.5 Character limits](#235-character-limits)
    - [2.4 Navigation objects](#24-navigation-objects)
    - [2.7 Groups](#27-groups)
    - [2.7 Channel names](#27-channel-names)
    - [2.8 Media types](#28-media-types)
    - [2.9 Media library](#29-media-library)
    - [2.5 File names](#25-file-names)
    - [2.10 Metadata](#210-metadata)
- [References](#references)

<!-- /MarkdownTOC -->


## 1. Introduction

TERMINALFOUR is the company based in Dublin, and the software is also called TERMINALFOUR. In this document the software will be refered to as T4 and the company as TERMINALFOUR. 

Any new T4 assests MUST use these guidelines for naming.

---

## 2. T4 Assets

TODO: make sure section numbering is correct 

### 2.1 Section names

TODO: URL naming conventions need to be discussed or we need to know.

In T4 section names become the URL unless the output URI is specified, therefore the output URI MUST be defined. Output URI MUST use hyphens to separate words and all lower case letters.

```
events
current-students
alumni-and-development
```


For subjects they MUST have the subject first, then followed by speciality or otherwise

```
english
english-creative-writing
physics
physics-pod
```
### 2.2 Page layouts

TODO: Discuss more if we will need more than 1 or 2 page layouts. May remove this section if needed.
TODO: Need to research/test what is capable with programmable layouts

### 2.3 Content types

Content types should correspond 1 to 1 with the patterns in the Digital Pattern Library, except when more are required to build the element.

#### 2.3.1 Content names

In each content item they MUST have the content type name followed by a short description of its use. That way it's easy to see from the admin menu what type of content we're working with.

```
Navbox - Guardbridge energy project
Staff profile - Principal, Joe Smith
```

#### 2.3.2 Content type formatters

Name element field should never be output, as this is named to make things easier on the admin end.

TODO: More here?

#### 2.3.3 Content type elements

Element names need to be straightforward and simple. Description must also be filled out (unless the name alone is sufficent, eg. Section links).

#### 2.5.4 List items

Try to make lists as reusable as you can, and make the list and list items names simple but descriptive. 

eg. To control the sizing of an element you make a list holding various bootstrap sizing classes. Name this `Bootstrap sizing` and elements `Small` with a value of `col-sm-4` and etc.

#### 2.3.5 Character limits

In general we have several levels of character limits.

*Usage* | *Character limit* 
--- | --- 
Title / button text | 80
Links / small items | 1024-2048
Plain text | 25,000
General / Large containers  | 96,000

### 2.4 Navigation objects

Navigation objects will primarily sit in page layouts, but still make them descriptive with their names, as the names now show up in the navigation object tag. We use a BEM-like naming for navigation objects.

BEM, meaning block, element, modifier, is a front-end methodology coined by developers working at Yandex. While BEM is a complete methodology, here we are only concerned with its naming convention. Further, the naming convention here only is BEM-like; the principles are exactly the same, but the actual syntax differs slightly.

BEM splits components' classes into three groups:

* Block: The sole root of the component.
* Element: A component part of the block.
* Modifier: A variant or extension of the block.

An example:

This is the template for related content:
 - page element - section this is for

e.g.
```
footer - scripts
```

Template for section details:
 - name of the nav object type - section it refers to / usage

e.g.
```
Generate file - file-name.txt
link - about
```

### 2.7 Groups

Users are NOT assigned things, rather we put Users in Groups and assign those Groups theings (Sections, Content types, page layouts, naviagtion objects, media library folders, etc). 

### 2.7 Channel names

We name channels and stuff.

### 2.8 Media types

Media types should be named following this structure:

File extension/*

e.g.
```
css/*
js/*
html/*
```

### 2.9 Media library

The media library should match the structure of the website. 

### 2.5 File names

Filenames

TODO for t4: Regex pattern: ```(([a-z])+-*)*.filename```

Following this convention:

- Files SHOULD be named descriptively using lowercase letters.
- Words MUST be separated by hyphens.
- Filenames MUST never end with .inc. If you use an included file use a double suffix: .inc.php.
```
filename.jpg
my-document-name.pdf
```

### 2.10 Metadata

We do metadata.

## References

