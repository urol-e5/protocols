---
layout: post
title: Surface Area Protocol
date: '2021-02-17'
categories: Protocols
tags: surface area, coral, physiology
projects: E5, Putnam Lab
---

# Standard protocol for coral surface area measurments using a paraffin wax bath

Original: 20210217
Last Revised: 20210217

**Contents**
- [**Materials**](#Materials)  
- [**Protocol**](#Protocol)
- [**References**](#References)

<a name="Materials"></a> **Materials**
  -    [Minerva paraffin wax bath](https://www.minervabeauty.com/digital-paraffin-wax-warmer?gclid=CjwKCAiAmrOBBhA0EiwArn3mfNRqPSXpWiILetogcl_4F_T27bdrLqC9FXPBtVWOapMeurZt758Y-xoChMUQAvD_BwE)
  -    Drying Oven (60°C)
  -    Analytical Balance
  -    [Variety of Wooden Dowels](https://www.etsy.com/listing/239645608/1-natural-wooden-balls-various-sizes?ga_order=most_relevant&ga_search_type=all&ga_view_type=gallery&ga_search_query=wooden+balls&ref=sr_gallery-1-1&external=1&from_market_listing_grid_organic=1&bes=1)
  -    [Gulf Wax Paraffin Wax](https://www.acehardware.com/departments/home-and-decor/canning/accessories-and-prep/62307?store=17544&gclid=CjwKCAiAmrOBBhA0EiwArn3mfLNmNjycQv7xrYlE2nX0ahIC3wc74MiGOsBBFwEFISTcu-wP7sVrehoCkNsQAvD_BwE&gclsrc=aw.ds)
  -    Small Twizzers
  -    Large Twizzers
  -    Permanent Marker
  -    Aluminum Foil


<a name="Protocol"></a> **Protocol**

#### Creating the surface area standard curve of mass change of wax dipped dowels against geometrically calculated surface area. You want your standard curve to have an an R<sup>2</sup> value greater than 0.9.

1.  Make a table with the known dimensions of your wooden dowels to be used as standards:

      **colony_id**|**sample**|**diameter**|**weight1.g**|**weight2.g**|
      :-----:|:-----:|:-----:|:-----:|:-----:|
      Standard1	|Standard	|7.44
      Standard2	|Standard	|6.22
      Standard3	|Standard	|5.08
      Standard4	|Standard	|3.16
      Standard5	|Standard	|2.52
      Standard6	|Standard	|1.9
      Standard7	|Standard	|1.18

1.  Label wooden dowels with a sample number using a permanent marker if they are not labeled already.
1.  Turn on the Minerva Paraffin Wax Bath and set it to 65 °C ~5 hours before wax dipping.
1.  Take an initial weight of each wooden dowel using the analytical scale to the nearest 0.0001 grams.
1.  Using the small or large twizzers (depends on the size of the dowel), submerge the wooden dowel into the paraffin wax dipping bath for 2 seconds.
1. Remove the wooden dowel and rotate the sample quickly in the air in a circular motion for 10 revolutions.
1.  Repeat for each of the wooden dowels.
1.  Place wax dipped dowels on a sheet of aluminum foil.
1.  Allow the dowels to cool to room temperature before taking the final wax weight (~15-20 minutes).
1.  Once the wax dipped dowels have dried fully, take the final weight using the analytical scale to the nearest 0.0001 grams.
1.  Enter the initial and final weights into your spreadsheet.

#### The rest of this protocol is completed in the [surface area script](https://github.com/urol-e5/timeseries/blob/master/timepoint_1/scripts/surface_area.Rmd)

1.  Using the diameter (mm) of your wooden dowels, calculate the radius.
  - Radius (r) = diameter (D) / 2.
2.  Calculate the surface area of your wooden dowels using the surface area equation:
  - SA = 4πr<sup>2</sup>
3.  Plot the relationship of the surface area (cm<sup>2</sup>) on the x-axis to the weight of the wax (g) on the y-axis to check if your standard curve has an R<sup>2</sup> value greater than 0.9.
4. Using the plot, calculate the curve coefficients for the slope and the y-intercept to apply as the standard (this information will be used later to calculate the surface area for your samples).
  - y=mx+b
  - x=(y-b)/m
  - slope = 0.025
  - y-intercept = 0.0043

![Example Standard Curve](https://raw.githubusercontent.com/urol-e5/protocols/master/images/SA_StCurve.png)



#### Measuring coral surface area

1.  After following the [airbrushing protocol](https://github.com/urol-e5/protocols/blob/master/2020-01-01-Airbrushing.md) on fresh or thawed corals, place coral skeletons on labeled aluminum foil in the drying oven at 60 °C for 4 h.
1.  Once the coral skeletons are dry (make sure there are no water droplets left), weigh the coral skeletons to the nearest 0.0001 grams.
1.  Using the tweezers, grab the base of the coral skeleton, if you can see where there was dead tissue, use this area to hold onto the skeleton.   
    - You want to make sure you are submerging all areas of the coral skeleton that had tissue cover.
1.   Once the wax is liquified (make sure there are no bubbles or solid pieces of wax left in the bath), fully submerge each coral skeleton into the bath for 2 seconds, remove the coral skeleton and rotate the sample quickly in the air in a circular motion for 10 revolutions.
1.  Place dipped coral skeletons onto labeled aluminum foil.
1.  Allow coral skeletons to dry to room temperature before taking the final weight.
1.  Once the dipped corals cool to room temperature, weigh each coral sample to the nearest 0.0001 grams.
1.  Make a table to calculate the surface area of your individual samples.

  **colony_id**|**sample**|**diameter**|**weight1.g**|**weight2.g**|
  :-----:|:-----:|:-----:|:-----:|:-----:|
  ACR-139	|Coral	|NA	|4.1315|	4.4772
9. Use the [surface area script](https://github.com/urol-e5/timeseries/blob/master/timepoint_1/scripts/surface_area.Rmd) to create an output file with your samples surface area values.



<a name="References"></a> **References**

  -  Stimson, J. and Kinzie III, R.A., 1991. The temporal pattern and rate of release of zooxanthellae from the reef coral Pocillopora damicornis (Linnaeus) under nitrogen-enrichment and control conditions. Journal of Experimental Marine Biology and Ecology, 153(1), pp.63-74.
  -  Veal, C.J., Carmi, M., Fine, M. and Hoegh-Guldberg, O., 2010. Increasing the accuracy of surface area estimation using single wax dipping of coral fragments. Coral Reefs, 29(4), pp.893-897.
