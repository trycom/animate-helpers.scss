animate-helpers.scss
====================

OOCSS helpers for [animate.scss](https://github.com/jackilyn/animate.scss) that make CSS animate.scss more declarative and more easily customisable

#### Usage
    @import "_animate-helpers.scss";
	@import "_animate.scss";
	
#### HTML example
###### fast fadeOut
   
    <div class="ani ani-fast fadeOut">

#### CSS example
###### fadeOut animation with a custom duration
    .custom-animation {
	  @extend .ani;
	  @extend .fadeOut;
	  @include ani-duration(10s);
    }


#### MIT
