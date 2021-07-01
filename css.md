{
.text > .header > .name::after, .reply > .header > .name::after {
     content: 'chad';
     position: relative;
     top: -1px;
     left: 4px;
     padding: 5px 8px;
     border-radius: 10px;
     font-size: 1.2rem;
     font-family: "Times New Roman", Times, serif;
     font-weight: bold;
     color: #fff;
     transition: .5s;
     animation-duration: 10s;
     animation-iteration-count: infinite;
     animation-name: rainbow;
     animation-timing-function: ease-in-out;
}


 .about > .content-wrap {
 border-style: solid;
  border-width: thin;
  border-color: rgba(61, 180, 242);
  background: rgba(0,0,0,0.5);
}


 .overview .wrap, .overview .content-wrap {
  border-style: solid;
  border-width: thin;
  border-color: rgba(61, 180, 242);
   background: rgba(0,0,0,0.5);
}

 .favourite {
  border-style: solid !important;
  border-width: thin !important;
  border-color: rgba(61, 180, 242) !important;
   background: rgba(0,0,0,0.5);
}

 .input{
 border-style: solid;
  border-width: thin;
  border-color: rgba(61, 180, 242);
   background: rgba(0,0,0,0.5);
}
  .stats-wrap > .list-stats, .page-content.wrap, .reply, .load-more, .el-textarea{
  border-style: solid;
  border-width: thin;
  border-radius: 20px;
  border-color: rgb(61, 180, 242);
   background: rgba(0,0,0,0.5);
  overflow: hidden !important;
}
.content.container{
  background: transparent !important;
}
.nav-wrap {
    border-radius: 20px !important;
    border: solid 2px rgb(61, 180, 242);
    width: 80% !important;
    margin: 0 auto;
     background: rgba(0,0,0,0.5);
}
/* bobaque v1.5 */
/*go show love to akaashibaby and hrishidod <3 */

a[href="/user/Hrishidod/"]:not(.avatar):not(.user):not(.link):not(.primary-link)::after { content: 'dummiedod ' !important; }

/* background wallpaper */
body{
    cursor: url(https://tobiasahlin.com/static/cursors/default.png), auto;
    background-color: rgb(var(--color-foreground));
    background: url(https://i.postimg.cc/Fz2DXWSb/Pics-Art-06-15-01-46-45.jpg);
    background-position: center / 100%;
    background-repeat: no-repeat;
    background-size: cover;
    background-attachment: fixed;
}

/* transparent banner, use with background */
.banner[data-v-4f7beb35] { 
    background-image: none! important;
    background-color: rgb(36, 37, 56, 0);
}

 .logo img[data-v-4fbac4e1] {
    content: url(https://files.catbox.moe/4kb1xr.gif);
}
.logo:hover {
    transition: transform 0.69s ease-in-out;
    transform: scale(1.6);
    border-radius: 20px;
    overflow: hidden;
}
   
/* hides the HOH download button on banner */
.hohDownload {
    display: none;
}

/* modify scroll bar  */
::-webkit-scrollbar {
    width: 5px;
    background: #01232d;
    border-radius: 50px;
}
::-webkit-scrollbar-corner {
    background: #01232d;
}
::-webkit-scrollbar-thumb {
    background: #574b74;
    -webkit-border-radius: 1ex;
}

/* change the AL logo on top nav bar */
.logo img[data-v-4fbac4e1] {
    content: url(https://files.catbox.moe/4kb1xr.gif);
}

/* content container */
.content.container {
    background-color: rgba(0, 0, 0, 0);
    max-width: 80%;
    padding: 30px 30px;
    border-radius: 0 0 15px 15px;
}

/* modify activity status - overview - “dont bully me pls” - activity status replies - "”> corners rounded */
.wrap[data-v-1bf2cf4e] {
    border-radius: 15px 15px 15px 15px;
    overflow: auto;
}
.overview[data-v-5c30286e] .content-wrap {
    border-radius: 15px;
}
.input[data-v-c574a71c] {
border-radius: 12px;
}
.reply[data-v-732ef224] {
    border-radius: 15px;
}




/* modify overview stats */

.section > .stats-wrap > .list-stats > .stats-wrap {




   display: grid;


   grid-auto-flow: row;


   grid-row-gap: 10px;


   grid-template-columns: auto auto;


   padding: 20px 40px;


   text-align: left;


}







.section > .stats-wrap > .list-stats > .stats-wrap .stat:nth-child(1) {


   grid-row-start: span 2;


}







.section > .stats-wrap > .list-stats > .stats-wrap .stat:nth-child(1) .value {


   font-size: 5.5rem;


}







.section > .stats-wrap > .list-stats > .stats-wrap .stat .value {


   font-size: 1.2rem;


   padding-bottom: 0px;


}







.section > .stats-wrap > .list-stats > .stats-wrap .stat .label {


   font-size: 1.2rem;


}







.section


 > .stats-wrap


 > .list-stats:nth-child(1)


 .stat:nth-child(1)


 .label:before {


   content: '';


   mask: url(https://criolaservice.by/AL-css/svg/tv.svg) no-repeat 50% 50%;


   -webkit-mask: url(https://criolaservice.by/AL-css/svg/tv.svg) no-repeat 50% 50%;


   mask-size: cover;


   -webkit-mask-size: cover;


   width: 19px;


   height: 16px;


   margin-right: 5px;


   background-color: rgba(var(--color-text-light));


}







.section > .stats-wrap > .list-stats:nth-child(2) .stat:nth-child(1) .label,


.section > .stats-wrap > .list-stats:nth-child(1) .stat:nth-child(1) .label {


   display: flex;


   align-items: center;


   color: rgb(var(--color-text-light));


}







.section


 > .stats-wrap


 > .list-stats:nth-child(2)


 .stat:nth-child(1)


 .label:before {


   content: '';


   mask: url(https://criolaservice.by/AL-css/svg/book.svg) no-repeat 50% 50%;


   -webkit-mask: url(https://criolaservice.by/AL-css/svg/book.svg) no-repeat 50% 50%;


   mask-size: cover;


   -webkit-mask-size: cover;


   width: 13px;


   height: 16px;


   margin-right: 5px;


   background-color: rgba(var(--color-text-light));


}




/* hide the milestones/progress bar on the overview anime and manga stats */
.milestones[data-v-815ccddc] {
    display: none;
}
.progress[data-v-815ccddc] {
    display: none;
}

/* activity status small avatar -> circle frame */
.text .avatar[data-v-1bf2cf4e] {
    border-radius: 100%;
    transition: transform .6s;
}

/* activity status small avatar hover */
.text .avatar[data-v-1bf2cf4e]:hover {
    transform: scale(1.3);
}

/* activity status comment reply section small avatar -> circle frame */
.avatar[data-v-732ef224] {
    border-radius: 100%
    transition: transform .6s;
}

/* activity status comment reply section small avatar hover */
.avatar[data-v-732ef224]:hover {
    transform: scale(1.3);
}

/* favorite media section */
.favourite[data-v-3f86aedd] {
    transition: transform .6s;
    border-radius: 18%;
    position: static;
}

/* favourites media section > wrap */
.favourites-wrap[data-v-3f86aedd] {
    overflow: visible;
}

/* favorites media section > hover */
.favourite[data-v-3f86aedd]:hover {
    transform: scale(1.2);
    position: static;
}

/* pfp icons in social on nav bar => AL default social > hohsocial*/
.avatar[data-v-39573fe2] {
    border-radius: 100px;
    height: 80px;
    width: 80px;
    background-size: cover;
    background-repeat: no-repeat;
    background-position: 50%;
}
.user-follow .follow-card {
    background-color: rgba(0, 0, 0, 0);
}
.hohSocialContent .avatar {
    border-radius: 100px;
    height: 80px;
    width: 80px;
    background-size: cover;
    background-repeat: no-repeat;
    background-position: 100%;
}

/* change profile nav bar */
.nav-wrap[data-v-4f7beb35] {
    background: rgb(var(--color-foreground));
    width: 75%;
    margin: auto;
    border-radius: 20px;
}
.nav[data-v-4f7beb35] {
    font-size: 1.7rem;
    max-width: 1220px;
    text-align: center;
    padding: 0px;
}

/* modify genre overview */
.percentage[data-v-aedb6876] {
    display: none;
}

/* modifies load more button at the bottom of page */
.load-more[data-v-6f203cf2] {
    border-radius: 15px;
    padding: 7px;
}
