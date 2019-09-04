# What to do if you aren't sure

## General accessibility

Use the [accessibility checker](checker.html) and information given by the checker or use the page by Microsoft on [making your word documents accessible](https://support.office.com/en-gb/article/make-your-word-documents-accessible-to-people-with-disabilities-d9bf3683-87ac-47ea-b91a-78dcacb3c66d).

This should ensure that you have:
* Applied heading styles and paragraph formatting to your document;
  * Every part of your document should be styled. This helps with navigation which is, arguably, more important in a mathematical document as when we read mathematics we move backwards and forwards checking things far more than when reading other text.
  * Heading styles also enable a reader to rapidly apply a personal theme to a document to meet their needs. 
* Added alternative text to images and other objects;
  * Writing alternative text for scientific images is not an easy task. [Benetech are the leader in providing advice on writing alt text for science](http://diagramcenter.org/) however you might also consider whether it is more appropriate to link to an alternative method of interaction which is accessible e.g. [Desmos](https://www.desmos.com/accessibility)
* Structured tables for easy navigation;

Think carefully about a fix particularly if it involves a mathematical element of the document. 

## Mathematical text

**All** mathematical text should be written using the Office equation editor. For instance, if you are writing about the variable $x$ it should be written as an equation. If you are writing $x^2$ it should be written as an equation.

* Never use insert symbol.
* Never write superscripts, subscripts, fractions etc. using font or style changes and standard keyboard input alone
* Never use an image of an equation.

You may find that [Getting started with effective entry of equations in Word](http://www.mathcentre.ac.uk/bathmash/Word/index.html) is useful to speed up the input of equations. Equations can be input using solely by typing. 

If you usually use [MathType](http://www.wiris.com/mathtype) then please reconsider until Wiris add functionality. The current situation is:

* Word format is accessible to some assistive technology. Some assistive technology has not yet implemented the interface (but could)
* MathType format is accessible to some assistive technology, including screenreaders which cannot yet access Word format
* MathType provides automatic **bulk** conversion of Word format **to** MathType format
* MathType only provides automatic **single equation** conversion to Word format **from** MathType

Hence, the most effective master format for accessibility purposes is Word with Word equation editor. 

### Remind me of why I need to follow these rules?

This enables assistive technology which can interact directly with equations in Word to work properly. It also ensures that automatic conversion is possible, using the structural integrity, to other formats which are accessible by other assistive technology. <!-- For a full overview of the current situation see the [table which tells us which AT works with which formats]().-->

[Return to plan](index.html)
