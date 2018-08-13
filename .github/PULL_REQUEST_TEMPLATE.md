---------------------------------------
## Changes this Pull Request Introduces
---------------------------------------
<!---Describe the big picture of your changes here to communicate to the reviewers why they should accept this pull request. If it fixes a bug or resolves a feature request, be sure to link to the trello card (if available).--->


---------------------------------------
## Reviewer's Checklist
---------------------------------------
This is a guideline for the reviewer on what to check to ensure that the quality of the code is kept at a Tink standard.  

_Put an `x` in the boxes that have been checked and fullfiled_ 

- [ ] The code packages follow the [Tink structure](https://docs.google.com/document/d/18pSzbRPlHYbKJtCDntMYE_4TqNWFdyTFuETq6lyNZBk/edit#heading=h.f3ao0xse8vu5)
- [ ] The code is clean from `development-only` code (setDebugOutput, println) 
- [ ] The known errors are being handled and unknown logged
- [ ] The `JSON/XML` values are sanitized (Not hardcoded from string concatenation of input values; Use `Jackson`!) 
- [ ] The code uses a [`Constants Class`](https://docs.google.com/document/d/18pSzbRPlHYbKJtCDntMYE_4TqNWFdyTFuETq6lyNZBk/edit#heading=h.6tr2fkwudh2m) for constants 
- [ ] The code uses `Catalog` for translatable strings
- [ ] The code follows the style, formatting and naming conventions of [Tink](https://docs.google.com/document/d/18pSzbRPlHYbKJtCDntMYE_4TqNWFdyTFuETq6lyNZBk/edit#heading=h.hxfhn3yt7me0)
- [ ] Follow the code for logical errors

---------------------------------------
## Further comments
---------------------------------------
<!---If this is a relatively large or complex change, kick off the discussion by explaining why you chose the solution you did and what alternatives you considered, etc...--->
