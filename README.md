# sass-mixin-margin-padding-responsive

SASS Mixin for margin and padding using breakpoints

usage: 
<div class="pb-xs-10 pb-lg-3 mt-sm-2">
  something...
 </div>
 
 compiled --->
 
 @media (min-width: 512px)
.pb-xs-10 {
    padding-bottom: 10rem;
}
@media (min-width: 1152px)
.pb-lg-3 {
    padding-bottom: 3rem;
}
@media (min-width: 768px)
.mt-sm-2 {
    margin-top: 2rem;
}
