## How to create an HTML code snippet that simulates a bookmark

<figure class="kg-card kg-bookmark-card">
    <a class="kg-bookmark-container" href="LINK_URL">
        <div class="kg-bookmark-content">
            <div class="kg-bookmark-title">TITLE</div>
            <div class="kg-bookmark-description">WRITE-UP</div>
            <div class="kg-bookmark-metadata">
                <img class="kg-bookmark-icon" src="FEATURE_IMAGE_URL">
                <span class="kg-bookmark-author">AUTHOR_NAME</span>
                <span class="kg-bookmark-publisher">PUBLISHER_NAME</span>
            </div>
        </div>
        <div class="kg-bookmark-thumbnail">
            <img src="THUMBNAIL_IMAGE_URL">
        </div>
    </a>
</figure>

There’s a few caveats you should be aware of though.

Don’t ask me why, but the author and publisher fields are reversed and so don’t correspond with their CSS classes. So in the above code, if you wanted to publish an article from the website Radio Ecoshock with the author Jane Doe, your code for the relevant portion would look like this:

<span class="kg-bookmark-author">Radio Ecoshock</span>
<span class="kg-bookmark-publisher">Jane Doe</span>

Note, however, that the formatting will look awry in the editor, but will end up looking correct in the draft/published post.