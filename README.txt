
Programming
-----------------------------------------------------------------------------
Development Language: C#

Framework: .Net framework

IDE: Visual Studio

Multi layer programming:

   Overbond solution contains:
  . Business Layer project, 
  . Model Layer project, 
  . Test Layer project


Solution
-----------------------------------------------------------------------------

## Challenge #1


Calculate the yield spread (return) between a corporate bond and its government bond benchmark. 

A government bond is a good benchmark if it is as close as possible to the corporate bond in terms of years to maturity (term).


## Solution #1
 Retrive data
 Calculate benchmark and diffrenece terms.
 Push benchmarks in the dictionary data type.
 Then retrive selected list.
 Finally, get greate term value.




## Challenge #2


The next challenge is calculate the spread to the government bond curve.

Since the corporate bond term is not exactly the same as its benchmark term, we need to use linear interpolation to dermine the spread to the curve.

## Solution #2
 Retrive data.
 Get maximum government bond.
 Get maximum coporatebond.
 Calculate interpolation.
 Finally, get coporate spread tocurve.
