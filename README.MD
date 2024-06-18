##### Website 
- website: generallly consists of static content that is delivered as a user requests it.
-Mostly informational.
-Blog pages,company pages,portfolios.
##### Web applications
-E-commerce pages,banking systems,social media platforms.
-Have functionalities attached like form inputs,dashboards,content management systems.
-Are interactive and dynamic.
-The backbone of any webpage is HTML.

##### HTML
-Defines the structure and content of a webpage.
-Uses tags and elements to define that structure(the layout and the content a user can see,paragraph,button,image,video) of the web page.
-syntax of HTML:
1.
<>: opening tag </> :closing tag
say a paragraph: <p> content </p>
                 <button> title  of the button </button>

</> closing tag
say img <img/>
br <br/> :<br>

2.Semantics:HTML provides semantic tags that provide specific meaning to content: Search Engine Optimization :
<header></header>: Heading section of the webpage.

<footer></footer> :defines the bottom section of a page
<nav></nav>:navigation.

3.Hyperlinks: HTML allows the linking of pages,external resources and internal resources and resources through hyperlink tags <a> tag: anchor tag,<link>

4.Forms and Input: Collect user input and interact with backend services.
<form>
<input/>email
<input/>password
<button>login <button>
</form>

comment tags are used to write notes with coding scripts.
<!--write comment-->

###### CSS(Cascading Style Sheets)
-Used to style and layout the web content structured by HTML.

1. Design and layout:controlling the visual appearance of a page.
2. Responsive design : CSS will allow us to adapt to different screen sizes and devices making the content accessible through all platforms.
:media queries and flexible grid layouts.

3. Animations and effects : creating visual effects (transitions).JS is more friendly.

#### syntax of CSS
Selectors : Element Name (p,button), elements id (#nameofid),class selector ( .nameofclass )

selector {
    stylingproperty : value
}
p {
    color : red;
}

#### How we write CSS
1. External CSS :link a HTML file to an external CSS file.Linked using link tag.
2. Internal CSS : Write css code inside the HTML document :using the <style></style>
3.Inline CSS : as an attribute for a HTML file

#### WORKING WITH GITHUB AND GIT
### SCENARIO A: COMMITING A NEW PROJECT

1. Create a new repository in github
2. Initializing the .git tracking folder for our local project
-git init
3. Connect our local project to the online repository .git option
git remote add origin https://github.com/StellaNjambi02/art_gallery.git
4. Confirm the link using : git remote -v
5. Check on files to be tracked
git status(red-not yet tracked,green-tracked)
6. Add files to be tracked
git add filename-file
git add foldername
git add . -all files
7. commit with a message
git commit -m "message value"
8. we can now push to our desired origin
-git push origin master/main(use git branch to check branch name)

#### pushing an existing project

assumptions: git repository exists,you have done an initial push

1. git status
2. git add . :: all files
git add file/folder name
3. git commit -m "message"
4. git push origin branchname