# Roam_Darkage
Dark Theme for Roam Research

/*/////////////////////////////////////*/
/*                                     */
/*     General Background Coloring     */
/*                                     */
/*/////////////////////////////////////*/

.roam-body-main {
    background-color: #282a2b;
}

#right-sidebar, .roam-topbar, .roam-sidebar-container {
    background-color: #1e1e1e !important;
}

.roam-block > span > div {
    background-color: inherit !important;
}

.rm-reference-item {
    background-color: #121212;
    background-color: rgba(255, 255, 255, .08);
}



/*//////////////////////////////*/
/*                              */
/*     General Text Styling     */
/*                              */
/*//////////////////////////////*/

.roam-body .roam-app .roam-sidebar-container .roam-sidebar-content .starred-pages-wrapper .starred-pages .page {
    color: #9eadb9;
}

.roam-body .roam-app {
    color: #FFFFFF;
    color: rgba(255, 255, 255, .60);
}

h1, h2, h3 {
    color: #b49d7d !important;
}

/* main link coloring + hover */
.rm-page-ref-link-color, a {
    color: #ff9500;
    transition: color .2s ease;
}

.rm-page-ref-link-color:hover, a:focus, a:hover {
    color: #ff6f00 !important;
    text-decoration: none !important;
    transition: color .2s ease;
}

/* remove underlining on links */
span {
    text-decoration: none !important;
}


/* path text color for linked references */
.parent-path-wrapper {
    color: #b49d7d;
}

/* block reference */
.roam-block .rm-block-ref {
    background-color: transparent !important;
    color: #e1c39a;
    border-bottom: 1px solid rgba(255,255,255,.2)
}

.rm-block-ref:hover {
    background-color: transparent !important;
    border-bottom: 1px solid rgba(255, 152, 0, .6);
}

/*////////////////////////////////*/
/*                                */
/*     Container Sizing Fixes     */
/*                                */
/*////////////////////////////////*/

.roam-article {
    width: 1200px;
}

.roam-block-container {
    max-width: 1000px;
}



/*///////////////////*/
/*                   */
/*     Search Box    */
/*                   */
/*///////////////////*/

.bp3-input {
    background: #FFFFFF;
    background: rgba(255, 255, 255, .05);
}

.bp3-input-group input {
    color: white !important
}



/*//////////////*/
/*              */
/*     ToDos    */
/*              */
/*//////////////*/

.check-container input:checked ~ .checkmark {
    background-color: #FFFFFF;
    background-color: rgb(27, 159, 28);
}



/*//////////////////*/
/*                  */
/*     Highlight    */
/*                  */
/*//////////////////*/

.roam-highlight {
    color: #d8dadb;
    background-color: #488244;
}



/*///////////////////////////////////*/
/*                                   */
/*     Code & Code Block styling     */
/*                                   */
/*///////////////////////////////////*/

code {
    background: #121212;
    background: rgba(18, 18, 18, 0.60);
    color: #c78741;
    border: 1px solid #000000;
    border: 1px solid rgba(18, 18, 18, 0.87);
}

.CodeMirror {
    background-color: #282a2b !important;
    color: #dbba96;
}

.CodeMirror-gutter-elt, .CodeMirror-gutter {
    background-color: #282a2b !important;
    color: #666;
}

.CodeMirror-line {
    padding-left: 6px !important;
}

.CodeMirror-gutters {
    border-right: 1px solid #666;
    background-color: #f7f7f7;
    white-space: nowrap;
}

.cm-s-default .cm-keyword {
    color: #d26ae1;
}

.cm-s-default .cm-number {
    color: #0cb974;
}

.cm-s-default .cm-meta {
    color: #959595;
}

.cm-s-default .cm-error {
    color: #cc4f4f;
}

.CodeMirror-selected {
    background-color: #655959 !important;
}



/*/////////////////////////*/
/*                         */
/*     Hashtag Styling     */
/*                         */
/*/////////////////////////*/

.rm-page-ref-tag {
 
    color: #3db5e1 !important;
    transition: color .2s ease;
}

.rm-page-ref-tag:hover {
    color: #ee6b00 !important;
    text-decoration: none;
    transition: color .2s ease;
}



/*///////////////////////////*/
/*                           */
/*     Namespace Styling     */
/*                           */
/*///////////////////////////*/

.rm-page-ref-namespace-color {
    color: #65bf38;
    transition: color .2s ease;
}

.rm-page-ref-namespace-color:hover {
    color: #bcff9a;
    text-decoration: none;
    transition: color .2s ease;
}



/*/////////////////////////////////////*/
/*                                     */
/*     "All Pages" Section Styling     */
/*                                     */
/*/////////////////////////////////////*/

.rm-pages-row {
    background-color: #282a2b !important;
    border-bottom: 1px solid #ffffff42;
}

.rm-pages-row-highlight {
    background-color: #282a2b
}

/* Page Name */
.bp3-text-overflow-ellipsis a {
    color: #b49d7d !important
}

/* Title Header */
.bp3-text-overflow-ellipsis, .rm-pages-sort-header {
    color: #ff9500;
}



/*///////////////////////////////*/
/*                               */
/*     Dropdown Menu Styling     */
/*                               */
/*///////////////////////////////*/


.bp3-popover-content, .bp3-menu {
    background-color: #464545 !important;
}

.bp3-menu a:hover {
    background: #0000001c;
}



/*////////////////////////*/
/*                        */
/*     Button Styling     */
/*                        */
/*////////////////////////*/

.roam-block .bp3-button {
    background-color: #464545 !important;
    color: white !important;
    text-transform: uppercase;
    margin-right: 5px;
}

.roam-block .bp3-button:hover {
    background-color: #285d00 !important;
}



/*////////////////////////////////*/
/*                                */
/*     Embedded Block Styling     */
/*                                */
/*////////////////////////////////*/

.rm-embed-container:hover > .rm-embed-edit {
    right: 30px;
}

.rm-embed-inner-block-hide {
    margin-left: 0px !important;
}

.rm-embed-edit {
    z-index: 1000;
}



/*/////////////////////////////*/
/*                             */
/*     Kanban Card Styling     */
/*                             */
/*/////////////////////////////*/

.kanban-column-container, .kanban-board {
    background-color: #2b2a2a
}

.kanban-column {
    background-color: #3e3e3e
}

.kanban-card {
    background-color: #595959
}
