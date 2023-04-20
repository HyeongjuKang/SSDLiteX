# SSDLiteX

## Introduction
SSDLite is an improved version of SSD and being widely used.
However, it is not well discussed which difference they have.
In SSDLiteX, the difference is discussed,
	and better model will be suggested.

## Citing SSDLiteX
On preparing for the publication

## 1. Comparing SSD and SSDLite

### 1.1. Prior Box
SSD uses a box size of {0.1, 0.2, 0.37, 0.54, 0.71, 0.88} for VOC data set
and {0.07, 0.15, 0.33, 0.51, 0.69, 0.87} for MS COCO date set.
For aspect ratio, 
	SSD uses Type 1 for the first, fifth, sixth prior boxes 
		and Type 2 for the others.

SSDLite uses a box size of {0.2, 0.35, 0.5, 0.65, 0.8, 0.95} for MS COCO data set
	and aspect ratio of Type 3 for the first prior boxes
			and Type 2 for the others.

| Type		| (Size, Aspect Ratio) 				|
| Type 1	| (1,1) (sq 2,1) (1,2) (1,1/2)		|
| Type 2	| (1,1) (sq 2,1) (1,2) (1,1/2) (1,3) (1,1/3)	|
| Type 3	| (1/2,1) (1,2) (1,1/2)				|

