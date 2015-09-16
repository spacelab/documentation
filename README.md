# Functions

# Mixins

# Base

* settings
* root
* document
* links
* lists
* media
* typography

# Objects

* margins
* media
* block
* flag
* grid
* list bare
* list inline
* list stacked
* list overflow

## objects.media

### Components

* Image
* Body

### Modifications

* Image align horizontal
* Spacing between elements
* Compontent is nestable

### Styles

	.o-media {
		display: block;
	}

	.o-media__body {
		display: block;
		overflow: hidden;
	}

	.u-image--left > .o-media__image {
		float: left;
	}

	.u-image--right > .o-media__image {
		float: right;
	}

	.u-image--left.u-spacing--base > .o-media__image {
		margin-right: $base-spacing;
	}

	.u-image--left.u-spacing--half > .o-media__image {
		margin-right: $base-spacing--half;
	}

	.u-image--left.u-spacing--quarter > .o-media__image {
		margin-right: $base-spacing--quarter;
	}

	.u-image--left.u-spacing--double > .o-media__image {
		margin-right: $base-spacing--double;
	}

	.u-image--left.u-spacing--quadruple > .o-media__image {
		margin-right: $base-spacing--quadruple;
	}

	.u-image--right.u-spacing--base > .o-media__image {
		margin-left: $base-spacing;
	}

	.u-image--right.u-spacing--half > .o-media__image {
		margin-left: $base-spacing--half;
	}

	.u-image--right.u-spacing--quarter > .o-media__image {
		margin-left: $base-spacing--quarter;
	}

	.u-image--right.u-spacing--double > .o-media__image {
		margin-left: $base-spacing--double;
	}

	.u-image--right.u-spacing--quadruple > .o-media__image {
		margin-left: $base-spacing--quadruple;
	}

### Markup

	<div class="o-media [ u-clearfix ] [ u-image--left u-image--right ] [ u-spacing--base u-spacing--half u-spacing--quarter u-spacing--double u-spacing--quadruple ]">
		<div class="o-media__image"></div>
		<div class="o-media__body"></div>
	</div>

## objects.block

### Components

* Header
* Image
* Body
* Footer

### Modifications

* Text align
* All components are optional and interchangable
* Image and body can have multiple instances
* Spacing between elements

## objects.flag

### Components

* Image
* Body

### Modifications

* Image align horizontal
* Body align vertical
* Spacing between elements
* Compontent is nestable
