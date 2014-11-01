# MAYDAY.US Campaign Specs

1. Responsive Content
2. Key Creative Assets
3. Primary Content Page
4. Homepage banner
5. Promotional Images for Social Media
6. MAYDAY.US Styling Guidelines
  1. 1.Colors
  2. 2.Fonts

These guidelines are intended to provided details guidance for the development of creative assets for MAYDAY campaigns. In the real life of campaign work, our timelines may not allow detailed consideration of all the specifications outlined below. Still, please keep in mind our desire to create responsive content while limiting the time required for front-end development work.

## Responsive Content

We do our best to ensure that our online presence is responsive. Our audience tends to be more tech savvy than most, and as such our audience browser windows tend to be mobile devices or very large screens. Approximately 29% of users are under 768px wide while 50% are more than 1344px wide.

## Key Campaign Executions

While some activities may only require a homepage, any new campaign or promotional content should ideally include the following creative assets:

- Primary content page
- Homepage banner
- Promotional Images for Social Media



Globally, our website uses Bootstrap's grid and break points as follows. While some content can flow outside of this range and images can scale as percentages, please note that outside of these limits, some content will be cut off for users with smaller browser windows.

| **Browser Size** | **Normal Content Size** | **No Padding Content Size** |
| --- | --- | --- |
| <768px | (scales) | (scales) |
| 768px - 991px | 750px | 768px |
| 992px - 1200px | 970px | 992px |
| >1200px | 1170px | 1200px |

## Primary Content Page

Example pages: 

* https://mayday.us/campaigns/maydayin30/ - html
* https://mayday.us/campaigns/of-course-brown-is-a-lobbyist/ - landing page

Basic Requirements:

- While we have maximum flexibility here, all content pages will need the standard MAYDAY.US header and footer.
- Depending on the action, the menu items in the MAYDAY header may be removed to focus users attention on any in-page "Call to Action" items.
- All images should be web-optimized

In the past, we have:

- **Used an Image only** - If font sizes is large enough, one image may be used and scaled down from 1170px wide down to 750px wide. (See: bootstrap constraints above) If font sizes are too small when the image is scaled down to 750px, we've created multiple images for each breakpoint in our grid system - 750px W, 970px W and 1170 px wide.
- **Sliced PSDs into grid based responsive HTML** - While producing custom CSS/HTML for different campaigns looks the best, it requires more tech lift and should be avoided. Please discuss w/ MAYDAY core team if this will be necessary.
- **Sliced PSDs into Full Width responsive HTML**: Grid system be damned! This also requires a bit of tech lift. Again, Please discuss w/ MAYDAY core team if this will be necessary for new creative content. Note: MAYDAY header and footer still required.

## Homepage banner

[Example here](https://github.com/MayOneUS/campaign_specs/blob/master/MAYDAY_simple_homepage_non_bleed_example.png).

The homepage banner is the trickiest part. Typically, any graphic content is accompanied by a headline and copy that is floated right with a width of appx 40%. We put together two simplified examples of the homepage banner - one bleed, one non-bleed. You can view in this repo.

Note: In these examples, graphic elements can exist outside the safe zones, but on the bleed graphic, the BG should be quite plain as text is overlayed on it.

**Full Details**:

| **Browser Size** | **Homepage Safezone w/ Copy** | **Homepage Safe Zone (no copy)** | **Homepage Full Width** |
| --- | --- | --- | --- |
| <768px | No visual | (scales) | (scales) |
| 768px - 991px | 450px | 750px | up to 991px |
| 992px - 1200px | 970px | 970px | up to 1200px |
| >1200px | 700px | 1170px | ∞ \* |

\* Infinity! Realistically: 1920px wide is the sweet spot.

## Promotional Images for Social Media

If time and resources allow, relevant image for social media sharing are helpful. General requirements:

|  | recommended | min | max |
| --- | --- | --- | --- |
| Twitter | 506x253 | 440x220 | 1024x512 |
| Facebook | 1200x627 | 484x252 | 1200x627 |

The images can be web optimized jpg, png or gif.

## MAYDAY.US Styling Guidelines

New content need strictly conform to existing design guidelines, but if you can complement the existing colors/fonts, please do.

### Colors

- MAYDAY red: #cc3333
- MAYDAY background: #f9fbfc
- MAYDAY Blue: #15405e

### Fonts

All our fonts are from Google Fonts. You can find this in this repo, or download them from their sources below:

- Body Copy: Merriweather ([Download](http://www.fontsquirrel.com/fonts/merriweather))
- Headlines: "Roboto" or "Roboto Condensed" ([Download](http://www.fontsquirrel.com/fonts/roboto))
- Headlines (phasing out): Questrial
- Iconography: [font-awesome](http://fortawesome.github.io/Font-Awesome/)
