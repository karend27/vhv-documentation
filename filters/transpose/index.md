---
transpose: transpose filter
author: Craig Stuart Sapp
creation_date: 23 Apr 2017
last_updated: 23 Apr 2017
tags: [all, filters]
sidebar: main_sidebar
verovio: "true"
keywords: interface commands 
summary: 
permalink: /filters/transpose/index.html
---

The transpose filter can be used transpose music by a specified
interval or to a specific key.

Here is an example of transposing a four-part chorale
from G major to A-flat major:

{% include verovio.html
	source="chorale"
	scale="40"
	pageWidth="1350"
	tabsize="10"
%}

<script type="application/json" id="chorale">
!!!filter: transpose -k a-
**kern	**kern	**kern	**kern
*Ibass	*Itenor	*Ialto	*Isoprn
*clefF4	*clefGv2	*clefG2	*clefG2
*k[f#]	*k[f#]	*k[f#]	*k[f#]
*G:	*G:	*G:	*G:
*M3/4	*M3/4	*M3/4	*M3/4
4GG	4B	4d	4g
=1	=1	=1	=1
4G	4B	4d	2g
4E	8cL	4e	.
.	8BJ	.	.
4F#	4A	4d	4dd
=2	=2	=2	=2
4G	4G	2d	4.b
4D	4F#	.	.
.	.	.	8a
4E	4G	4B	4g
=3	=3	=3	=3
4C	8cL	8eL	4.g
.	8BJ	8d	.
8BBL	4c	8e	.
8AAJ	.	8f#J	8a
4GG	4d	4g	4b
=4	=4	=4	=4
2D;	2d;	2f#;	2a;
4GG	4d	4g	4b
=5	=5	=5	=5
4FF#	4A	4d	2dd
4GG	4B	4e	.
4AA	4c	4f#	4cc
=6	=6	=6	=6
4BB	4d	2g	4b
4C	4e	.	2a
4D	8dL	4f#	.
.	8cJ	.	.
=7	=7	=7	=7
2GG;	2B;	2d;	2g;
=:|!	=:|!	=:|!	=:|!
4GG	4d	[4g	4b
=8	=8	=8	=8
4GG	4d	8gL]	4b
.	.	8f#J	.
4AA	4c	8eL	4cc
.	.	8f#J	.
4BB	8BL	[4g	4dd
.	8AJ	.	.
=9	=9	=9	=9
4.BB	8BL	8gL]	4.dd
.	8cJ	8aJ	.
.	4d	8gL	.
8AA	.	8f#J	8cc
4GG	4d	4g	4b
=10	=10	=10	=10
2D;	2d;	2f#;	2a;
[4E	4B	4e	4g
=11	=11	=11	=11
4E]	4G	4e	2b
4D	4B	8f#L	.
.	.	8gJ	.
4C	4e	4a	4cc
=12	=12	=12	=12
4.BB	2d	4a	2dd
.	.	4.g	.
8C	.	.	.
4D	4d	.	4cc
.	.	8f#	.
=13	=13	=13	=13
8GGL	2.d	2g	2.b
8AAJ	.	.	.
4BB	.	.	.
4GG	.	4f	.
=14	=14	=14	=14
2C;	2c;	2e;	2g;
4GG	4d	4g	4b
=15	=15	=15	=15
4FF#	8dL	4.a	2dd
.	8cJ	.	.
4GG	4B	.	.
.	.	8g	.
4AA	4c	4f#	4cc
=16	=16	=16	=16
4BB	2d	2g	2b
4GG	.	.	.
4D	8dL	[4f#	4a
.	8cJ	.	.
=17	=17	=17	=17
8EL	4B	8f#L]	4.g
8D	.	8eJ	.
8C	4c	8eL	.
8BB	.	8f#J	8a
8AA	4d	4g	4b
8GGJ	.	.	.
=18	=18	=18	=18
2D;	2d;	2f#;	2a;
[4G	4d	4g	4b
=19	=19	=19	=19
4G]	2d	2a	2dd
4F#	.	.	.
[4E	4e	8gL	4cc
.	.	8f#J	.
=20	=20	=20	=20
8EL]	2e	2g	4b
8DJ	.	.	.
4C	.	.	2a
4D	8dL	4f#	.
.	8cJ	.	.
=21	=21	=21	=21
2GG;	2B;	2d;	2g;
==	==	==	==
*-	*-	*-	*-
</script>

Try changing `a-` to `a` in the filter line to transpose to A major instead.

The transpose filter is identical to the Humdrum Extras command-line tool
[transpose](http://extras.humdrum.org/man/transpose).  See its documentation for
more examples of how to use the transpose filter.


