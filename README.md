# ScaledOffset
Glyph script that will compute the centroid of a closed loop of connectors and create a scaled copy of the loop relative to the centroid of the loop.

## Operation
This script allows the user to select a loop of connectors that define the outer edge of a closed loop. A uniform scaling (as specified by the value of alpha on Line 33) will be applied, using the centroid of the loop. This script can be quite useful when manually creating an inflated layer when extrusions do not produce the deisred effect. Values of alpha < 1 will produce an offset loop that is smaller than the original; values of alpha > 1 will produce and offset loop that is larger than the original. In the image below, the yellow curve is the result of running the script with the outer loop selected with a value of alpha = 0.75.

When running the script, there are two methods of selecting the edges of the region: Select the edges of the loop prior to executing the script (works only for versions of Pointwise >= 17.2R2), or when prompted to select the connectors after executing the script.


![ScriptImage](https://raw.github.com/pointwise/ScaledOffset/master/ScriptImage.png)

## Disclaimer
Scripts are freely provided. They are not supported products of
Pointwise, Inc. Some scripts have been written and contributed by third
parties outside of Pointwise's control.

TO THE MAXIMUM EXTENT PERMITTED BY APPLICABLE LAW, POINTWISE DISCLAIMS
ALL WARRANTIES, EITHER EXPRESS OR IMPLIED, INCLUDING, BUT NOT LIMITED
TO, IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR
PURPOSE, WITH REGARD TO THESE SCRIPTS. TO THE MAXIMUM EXTENT PERMITTED
BY APPLICABLE LAW, IN NO EVENT SHALL POINTWISE BE LIABLE TO ANY PARTY
FOR ANY SPECIAL, INCIDENTAL, INDIRECT, OR CONSEQUENTIAL DAMAGES
WHATSOEVER (INCLUDING, WITHOUT LIMITATION, DAMAGES FOR LOSS OF BUSINESS
INFORMATION, OR ANY OTHER PECUNIARY LOSS) ARISING OUT OF THE USE OF OR
INABILITY TO USE THESE SCRIPTS EVEN IF POINTWISE HAS BEEN ADVISED OF THE
POSSIBILITY OF SUCH DAMAGES AND REGARDLESS OF THE FAULT OR NEGLIGENCE OF
POINTWISE.
	 

