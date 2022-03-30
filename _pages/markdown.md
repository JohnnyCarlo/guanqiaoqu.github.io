---
permalink: /projects/
author_profile: true
redirect_from: 
  - /md/
  - /markdown.html
---
<style type="text/css">
    h1 { counter-reset: h2counter; }
    h2 { counter-reset: h3counter; }
    h3 { counter-reset: h4counter; }
    h4 { counter-reset: h5counter; }
    h5 { counter-reset: h6counter; }
    h6 { }
    h2:before {
      counter-increment: h2counter;
      content: counter(h2counter) ".\0000a0\0000a0";
    }
    h3:before {
      counter-increment: h3counter;
      content: counter(h2counter) "."
                counter(h3counter) ".\0000a0\0000a0";
    }
    h4:before {
      counter-increment: h4counter;
      content: counter(h2counter) "."
                counter(h3counter) "."
                counter(h4counter) ".\0000a0\0000a0";
    }
    h5:before {
      counter-increment: h5counter;
      content: counter(h2counter) "."
                counter(h3counter) "."
                counter(h4counter) "."
                counter(h5counter) ".\0000a0\0000a0";
    }
    h6:before {
      counter-increment: h6counter;
      content: counter(h2counter) "."
                counter(h3counter) "."
                counter(h4counter) "."
                counter(h5counter) "."
                counter(h6counter) ".\0000a0\0000a0";
    }
</style>
<!---
change "permalink: /markdown/" to "permalink: /projects/"
-->
# Research Projects
## A Software Development (\*\*\*\*\*\*\*\*\*\*\*\*)~
* Basic Strengthening Key Projects
* Sep 2021 – Present
* Supervisor: Chenguang He, Lin Ma, Liang Ye, Weixiao Meng
* Details
  * Designed the communication scheme.
  * Proposed and simulated two communication algorithms according to the requirements of the nodes.
  * Tools: Linux, C++, MATLAB

## China-Chile ICT "The Belt and Road" Joint Laboratory Construction and Joint Research (SQ2020YFE020708)
* National Science and Technology Project
* Sep 2021 – Present
* Supervisor: Chenguang He, Shuyi Chen, Weixiao Meng
* Details
  * Designed the communication model for Massive IoT devices in areas without the cellular network to access the Internet with Vehicular ad hoc Networks.
  * Proposed the communication scheme to minimize total network energy consumption and maximize communication reliability by optimizing communication strategy and relay selection.
  * Designed the communication model for Massive IoT devices in areas without the cellular network to access the cellular network with vehicular Ad Hoc networks.
  * Proposed the communication scheme to minimize total network energy consumption and maximize communication reliability by optimizing communication strategy and relay selection.
  * Proposed the communication scheme to maximize the energy efficiency of transmitting Massive IoT packets from Massive IoT devices to the vehicles by jointly optimizing the network resources allocation and connection strategy.
  * Proposed the routing algorithm to decide data forwarding routes and offloading routes. 
  * Tools: MATLAB

## Research on \*\*\*\*\*\*\*\*\* and Transmission Optimization Technology (HHX20641X002)
* Enterprise Cooperation Project
* Sep 2020 – Oct 2020
* Supervisor: Chenguang He, Lin Ma, Liang Ye, Shuai Han, Weixiao Meng
* Details
  * Simulated parallel communications of nodes under AOMDV routing protocol and measured network performance.
  * Tools: Network Simulator version 2 (NS-2)

## Research on Communication Technology of Indoor-and-Outdoor Unmanned Clustering WANET (F2100115)
* Enterprise Cooperation Project
* Sep 2019 – Mar 2021
* Supervisor: Chenguang He, Lin Ma, Liang Ye, Shuai Han, Weixiao Meng
* Details
  * Made the network interface card into Ad Hoc networks by using AODV routing protocol.
  * Developed a program based on UDP protocol and socket interface to extend the simple case to the general case.  
  * Simulated the hop counts and delays when multiple virtual nodes communicate.
  * Tools: Linux, C++

## Research on Cluster Routing Algorithm Based on Vehicle Attribute Information for Vehicular Ad Hoc Network
* Bachelor thesis in HIT
* Sep 2019 – Jun 2020
* Supervisor: Chenguang He
* Details
  * Investigated the existing routing and clustering algorithms.
  * Proposed a cluster-and-routing algorithm based on vehicles’ information to meet the demand for efficient and stable low-latency routes.
  * Tools: NS-2, Simulation of Urban MObility (SUMO), MATLAB











<!---
## Locations of key files/directories

* Basic config options: _config.yml
* Top navigation bar config: _data/navigation.yml
* Single pages: _pages/
* Collections of pages are .md or .html files in:
  * _publications/
  * _portfolio/
  * _posts/
  * _teaching/
  * _talks/
* Footer: _includes/footer.html
* Static files (like PDFs): /files/
* Profile image (can set in _config.yml): images/profile.png

## Tips and hints

* Name a file ".md" to have it render in markdown, name it ".html" to render in HTML.
* Go to the [commit list](https://github.com/academicpages/academicpages.github.io/commits/master) (on your repo) to find the last version Github built with Jekyll. 
  * Green check: successful build
  * Orange circle: building
  * Red X: error
  * No icon: not built

## Resources
 * [Liquid syntax guide](https://shopify.github.io/liquid/tags/control-flow/)

## Markdown guide

### Header three

#### Header four

##### Header five

###### Header six

## Blockquotes

Single line blockquote:

> Quotes are cool.

## Tables

### Table 1

| Entry            | Item   |                                                              |
| --------         | ------ | ------------------------------------------------------------ |
| [John Doe](#)    | 2016   | Description of the item in the list                          |
| [Jane Doe](#)    | 2019   | Description of the item in the list                          |
| [Doe Doe](#)     | 2022   | Description of the item in the list                          |

### Table 2

| Header1 | Header2 | Header3 |
|:--------|:-------:|--------:|
| cell1   | cell2   | cell3   |
| cell4   | cell5   | cell6   |
|-----------------------------|
| cell1   | cell2   | cell3   |
| cell4   | cell5   | cell6   |
|=============================|
| Foot1   | Foot2   | Foot3   |

## Definition Lists

Definition List Title
:   Definition list division.

Startup
:   A startup company or startup is a company or temporary organization designed to search for a repeatable and scalable business model.

#dowork
:   Coined by Rob Dyrdek and his personal body guard Christopher "Big Black" Boykins, "Do Work" works as a self motivator, to motivating your friends.

Do It Live
:   I'll let Bill O'Reilly [explain](https://www.youtube.com/watch?v=O_HyZ5aW76c "We'll Do It Live") this one.

## Unordered Lists (Nested)

  * List item one 
      * List item one 
          * List item one
          * List item two
          * List item three
          * List item four
      * List item two
      * List item three
      * List item four
  * List item two
  * List item three
  * List item four

## Ordered List (Nested)

  1. List item one 
      1. List item one 
          1. List item one
          2. List item two
          3. List item three
          4. List item four
      2. List item two
      3. List item three
      4. List item four
  2. List item two
  3. List item three
  4. List item four

## Buttons

Make any link standout more when applying the `.btn` class.

## Notices

**Watch out!** You can also add notices by appending `{: .notice}` to a paragraph.
{: .notice}

## HTML Tags

### Address Tag

<address>
  1 Infinite Loop<br /> Cupertino, CA 95014<br /> United States
</address>

### Anchor Tag (aka. Link)

This is an example of a [link](http://github.com "Github").

### Abbreviation Tag

The abbreviation CSS stands for "Cascading Style Sheets".

*[CSS]: Cascading Style Sheets

### Cite Tag

"Code is poetry." ---<cite>Automattic</cite>

### Code Tag

You will learn later on in these tests that `word-wrap: break-word;` will be your best friend.

### Strike Tag

This tag will let you <strike>strikeout text</strike>.

### Emphasize Tag

The emphasize tag should _italicize_ text.

### Insert Tag

This tag should denote <ins>inserted</ins> text.

### Keyboard Tag

This scarcely known tag emulates <kbd>keyboard text</kbd>, which is usually styled like the `<code>` tag.

### Preformatted Tag

This tag styles large blocks of code.

<pre>
.post-title {
  margin: 0 0 5px;
  font-weight: bold;
  font-size: 38px;
  line-height: 1.2;
  and here's a line of some really, really, really, really long text, just to see how the PRE tag handles it and to find out how it overflows;
}
</pre>

### Quote Tag

<q>Developers, developers, developers&#8230;</q> &#8211;Steve Ballmer

### Strong Tag

This tag shows **bold text**.

### Subscript Tag

Getting our science styling on with H<sub>2</sub>O, which should push the "2" down.

### Superscript Tag

Still sticking with science and Isaac Newton's E = MC<sup>2</sup>, which should lift the 2 up.

### Variable Tag

This allows you to denote <var>variables</var>.

--> 
