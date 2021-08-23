# grid-to-plot

This project enables you to fully custom design a github profile contribution grid.

The grid is bound by the styling of github's front page, so the grid is always 7 pixels high. The width however is fully up to you.

---
> Currently you can enter an array in the `vm.demoArray`, with values ranging 0-4 and it will generate a grid filled in to match, or you can edit the displayed array in the text area. 
>
> If you want a different colour scheme, you can change which colours show up by changing the hex-codes in the `vm.colourScheme`. 
> By defaut it is set to the colours you see on the profile page (those beautiful greens).
>
> 
---
> ToDos;
> - Add Error Handling into textArea !important
> - Add Error Handling into width text input (not too big, too small (negative/0) and int) !important
> - Potential width editor in the main page
> - Add responsive design to page
> - Export custom grid to a script -> user downloadable file which will generate the contribution grid on your page.
---
_Template.txt contains a reference array just in case you delete the array stored in `vm.demoArray`._