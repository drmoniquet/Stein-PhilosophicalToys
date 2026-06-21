# Stein-PhilosophicalToys

Toy: ->https://drmoniquet.github.io/Stein-PhilosophicalToys/ 

These philosophical toys, created by Monique Tschofen and George Pechtol, test Gertrude Stein's experimental and playful approach to philosophy. Most readings of Gertrude Stein's Tender Buttons (1914) posit that what she is doing is offering a stream of consciousness, in the Jamesian sense, that is, her language is uncensored, unstructured, and unintentional. Yet a careful intertextual reading of the work shows something else. Stein was painting and sculpting the raw materials of philosophy. 

George and Monique asked how can we see this pattern of intertextual allusion at work?

To this moment, we have completed 11 of the 58 poems in *Objects* ("A Carafe," "Glazed Glitter," "A Substance in a Cushion," "A Box," "A Piece of Coffee," "A Seltzer Bottle," "Mildred's Umbrella," "A Chair," "More," "Malachite, and "A Table"); 4 snippets of pieces  from *Food*'s 43 poems ("Roastbeef," "Mutton," "Breakfast," "Milk"), and 15 fragments of the single continuous poem *Rooms*. This project will be expanded as we have time. The goal, however, isn't a footnoted critical edition of Stein's radical poetry, but rather an experimental demo of what lives inside it. The metaphor of her final section ROOMS and all the containers, carafes, cups, etc. that are held in the poem's spaces is therefore apt; Stein invites us to peer in and move through the spaces.      

**Design Notes:**
Background: 
- The paper texture is taken right from the first page of the Marie-Claire edition, and tiled throughout. 

Fonts:
- The bulk of the project is published in Libre Caslon Text and Libre Caslon Display, which are what Stein used when she published _Tender Buttons_ with Claire Marie in 1914. (You can see that edition here: https://archive.org/details/tenderbuttonsobj00steirich/page/n7/mode/2up?ref=ol)
- EB Garamond was used for the Greek characters and some editorial apparatus https://fonts.google.com/specimen/EB+Garamond

**The "blind" glass: **
The glass interface was designed to echo the cover design of the Clarie Marie edition of _Tender Buttons_ (1914) but also feel a bit like a magnifying glass. We wanted whatever sits under the glass to bend and ripple slightly, the way a text looks through an old hand-blown lens, so we used turbulence : https://www.smashingmagazine.com/2021/09/deep-dive-wonderful-world-svg-displacement-filtering/ (feTurbulence) was used to generate soft noise → feDisplacementMap warping the backdrop by it), applied to the lens as backdrop-filter: url(#glassRipple).

**Sources:**
We tried to find free online sources for all references, and list sources that informed Monique's thinking in the bibliography. Most of the Aristotle readings are on Perseus (Tufts), but Wikisource filled in some blanks.    


Monique Tschofen is Professor of English at Toronto Metropolitan University. Find her at https://sites.google.com/view/moniquetschofen/ 
Other philosophical Stein toys Monique has made include "In There, Behind the Door" https://scalar.usc.edu/works/in-there-behind-the-door-an-exhibition-of-deformances-of-gertrude-stein/index and "Careless Water | Streams of (Artificial) Thought" https://arcg.is/05GXOe0 
