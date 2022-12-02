# USPTO PDF output compliance      #2    

  [fledder](https://github.com/fledder)  opened this issue Dec 16, 2018 · 1 comment        

  

## Comments

### **[fledder](https://github.com/fledder)**                 commented       [Dec 16, 2018](https://github.com/PetePupalaikis/uspatent/issues/2#issue-391440603)       

​          Hi Pete, I am going to add issues for each of  the changes I've made use of, so hopefully we can discuss whether and  how to include them. Seems to be the way to do it in GitHub. I'd like to add a "strict" or "efile" mode that would  bring the output file into compliance with the requirements for efiling  listed here: https://www.uspto.gov/patents-application-process/applying-online/efs-web-pdf-guidelines This is generally easiest to achieve as a PDF/A compliant  document. I have gotten a local version of uspatent.cls to output PDF/A  using this guide: https://www.mathstat.dal.ca/~selinger/pdfa/ I think the easiest way to integrate this function with  the existing setup might be to make an "efile" or "strict" mode  alongside "draft" and "application". Thoughts?      

### **[fledder](https://github.com/fledder)**                 commented       [Dec 16, 2018](https://github.com/PetePupalaikis/uspatent/issues/2#issuecomment-447678264)       

​          Per our conversation, I will be working on this feature first and will send a pull request when we have that all figured out.   

  

#### [fledder](https://github.com/fledder)        added a commit        to fledder/uspatent      that referenced      this issue     [       Dec 21, 2018     ](https://github.com/PetePupalaikis/uspatent/issues/2#ref-commit-2675a90)

   `          Working on the issue PetePupalaikis#2        `          [2675a90](https://github.com/fledder/uspatent/commit/2675a904432317805636e02f8198d6decd4e9672)

```
Added a class option efileReady that enables the correct package for PDF/A output
Added a few lines to the documentation to point this out
Added metadata file PatentApplication.xmpdata (required for PDF/A)
```