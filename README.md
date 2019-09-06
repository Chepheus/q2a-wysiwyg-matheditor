# :black_nib: Q2A Math Editor (LaTeX)


## :clipboard: Description

This is a WYSIWYG Math formulas editor for [Question2Answers](https://www.question2answer.org/). 
 
Some history...

I made this plugin long time ago (right after the ckeditor 4 release) then I published it here looong time after (but already 5 years ago from now !). Finally today (september 2019) I'm updating to **fix mathjax issue** and while we are here I update it to latest **CKEditor 4** version and improve documentation :smile:  

Since I first released this, [Question2Answers](https://www.question2answer.org/) team integrated natively the [CKEditor 4](https://github.com/ckeditor/ckeditor-dev) as WYSIWYG :thumbsup:

But this plugin is still good if you want to have Math formulas.


## :speech_balloon: Feedback

Please report any issue in the [issue board](https://github.com/thibaultduponchelle/q2a-ckeditor-latex/issues), this is a beta testing release and I think there's some small fixes to do.


## :carousel_horse: Install 

1. Download the plugin
2. Decompress in your **qa-plugin** directory
3. Enable **WYSIWYG Math Editor** in the **Admin** > **Posting** page.

![](screenies/matheditors.png)

4. Enable **MathJax** on your website by putting this code into **Admin** > **Layout** > C**ustom HTML in HEAD** section of every page:

```
<script src="https://polyfill.io/v3/polyfill.min.js?features=es6"></script>
<script id="MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>
```

Like this : 

![](screenies/customhtml.png)

And you're done !

## :rainbow: Demo

When you go to post a question you will have this new WYSIWYG editor with an **Sigma** in the toolbar (+ various other plugins selected by me) : 

![](screenies/editor.png)

When you click on it the **Sigma** button you will have a popup and you can start editing **Math Formulas** with a visual feedback : 

![](screenies/editmath.png)

When you submit you message, you get your math YEAH : 

![](screenies/yeah.png)
