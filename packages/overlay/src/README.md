# orxe-overlay

```html
<!-- // Default -->
<orxe-overlay title='New Overlay' > 
<div slot="content"> 
	Overlay Content goes here
</div>
</orxe-overlay>

//area-label for close button
<orxe-overlay title='New Overlay' a11yLabelClose='Close Button' > 
<div slot="content"> 
	Overlay Content goes here
</div>
</orxe-overlay>

//overlay-type to define type of overlays
//values are popup-overlay, slider-overlay, full-overlay
 <orxe-overlay title='New Overlay slidee'  a11yLabelClose='Close Button' overlay-type='slider-overlay' > 
<div slot="content"> 
	Overlay Content goes here
</div>
</orxe-overlay>

//full overlay type with area-labels for buttons
<orxe-overlay title='New Overlay full page'  
	a11yLabelClose='Close Button' 
	overlay-type='full-overlay' 
	a11yLabelTertiary = 'Cancel Button'
	a11yLabelSecondary = 'Submit Button'; > 
<div slot="content"> 
	Overlay Content goes here
</div>
<span slot="tertiary-button" >Cancel</span>
<span slot="secondary-button" >Submit</span>
</orxe-overlay>


```

