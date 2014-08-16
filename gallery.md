---
layout: page
title: Gallery
permalink: /gallery/
---

<!-- The Bootstrap Image Gallery lightbox, should be a child element of the document body -->
<div id="blueimp-gallery" class="blueimp-gallery">
    <!-- The container for the modal slides -->
    <div class="slides"></div>
    <!-- Controls for the borderless lightbox -->
    <h3 class="title"></h3>
    <a class="prev">‹</a>
    <a class="next">›</a>
    <a class="close">×</a>
    <a class="play-pause"></a>
    <ol class="indicator"></ol>
    <!-- The modal dialog, which will be used to wrap the lightbox content -->
    <div class="modal fade">
        <div class="modal-dialog">
            <div class="modal-content">
                <div class="modal-header">
                    <button type="button" class="close" aria-hidden="true">&times;</button>
                    <h4 class="modal-title"></h4>
                </div>
                <div class="modal-body next"></div>
                <div class="modal-footer">
                    <button type="button" class="btn btn-default pull-left prev">
                        <i class="glyphicon glyphicon-chevron-left"></i>
                        Previous
                    </button>
                    <button type="button" class="btn btn-primary next">
                        Next
                        <i class="glyphicon glyphicon-chevron-right"></i>
                    </button>
                </div>
            </div>
        </div>
    </div>
</div>

<div id="links">
    <a href="{{ "/static/images/carousel1.jpg" | prepend: site.baseurl }}" title="Back of the Boat" data-gallery>
        <img src="{{ "/static/images/carousel1.jpg" | prepend: site.baseurl }}" alt="Back of the Boat" width="20%">
    </a>
    <a href="{{ "/static/images/carousel2.jpg" | prepend: site.baseurl }}" title="Some fish" data-gallery>
        <img src="{{ "/static/images/carousel2.jpg" | prepend: site.baseurl }}" alt="Some fish" width="20%">
    </a>
    <a href="{{ "/static/images/carousel3.jpg" | prepend: site.baseurl }}" title="Look at all these fish" data-gallery>
        <img src="{{ "/static/images/carousel3.jpg" | prepend: site.baseurl }}" alt="Look at all these fish"  width="20%">
    </a>
    <a href="{{ "/static/images/image1.jpg" | prepend: site.baseurl }}" title="Look at all these fish" data-gallery>
        <img src="{{ "/static/images/image1.jpg" | prepend: site.baseurl }}" alt="Look at all these fish"  width="20%">
    </a>
    <a href="{{ "/static/images/image2.jpg" | prepend: site.baseurl }}" title="Look at all these fish" data-gallery>
        <img src="{{ "/static/images/image2.jpg" | prepend: site.baseurl }}" alt="Look at all these fish"  width="20%">
    </a>
    <a href="{{ "/static/images/image3.jpg" | prepend: site.baseurl }}" title="Look at all these fish" data-gallery>
        <img src="{{ "/static/images/image3.jpg" | prepend: site.baseurl }}" alt="Look at all these fish"  width="20%">
    </a>
    <a href="{{ "/static/images/image4.jpg" | prepend: site.baseurl }}" title="Look at all these fish" data-gallery>
        <img src="{{ "/static/images/image4.jpg" | prepend: site.baseurl }}" alt="Look at all these fish"  width="20%">
    </a>
    <a href="{{ "/static/images/image5.jpg" | prepend: site.baseurl }}" title="Look at all these fish" data-gallery>
        <img src="{{ "/static/images/image5.jpg" | prepend: site.baseurl }}" alt="Look at all these fish"  width="20%">
    </a>
    <a href="{{ "/static/images/image6.jpg" | prepend: site.baseurl }}" title="Look at all these fish" data-gallery>
        <img src="{{ "/static/images/image6.jpg" | prepend: site.baseurl }}" alt="Look at all these fish"  width="20%">
    </a>
    <a href="{{ "/static/images/image7.jpg" | prepend: site.baseurl }}" title="Look at all these fish" data-gallery>
        <img src="{{ "/static/images/image7.jpg" | prepend: site.baseurl }}" alt="Look at all these fish"  width="20%">
    </a>
    <a href="{{ "/static/images/image8.jpg" | prepend: site.baseurl }}" title="Look at all these fish" data-gallery>
        <img src="{{ "/static/images/image8.jpg" | prepend: site.baseurl }}" alt="Look at all these fish"  width="20%">
    </a>

</div>
