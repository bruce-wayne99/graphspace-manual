# Commenting on Graphs

Comment-system allows user to comment on different graph components similar to add comments as a means to discuss or share ideas with their collaborators for a given graph, analogous to the way "Comments" on Google Docs allow users to discuss ideas on text documents.
. [GraphSpace](http://www.graphspace.org) allows users to comment on the following:

1. **Node** - Users can comment on a node.
2. **Edge** - Users can comment on an edge.
3. **Subgraph** - Users can comment on a combination of nodes and edges (a subgraph).

The following features are available in the Comment system functionality:
- [Adding comments](#adding-comments)
- [Viewing comments](#viewing-comments)
- [Replying to comments](#replying-to-comments)
- [Real-time experience of add and reply to comments](#real-time-experience-of-add-and-reply-to-comments)
- [Editing comments](#editing-comments)
- [Resolving comments](#resolving-comments)
- [Deleting comments](#deleting-comments)
- [Re-opening resolved comments](#re-opening-resolved-comments)
- [Real-time experience of edit resolve reopen and delete comments](#real-time-experience-of-edit-resolve-reopen-and-delete-comments)
- [Displaying comments associated with selected graph](#displaying-comments-associated-with-selected-graph)
- [Highlighting subgraph associated with a comment](#highlighting-subgraph-associated-with-a-comment)
- [Pinning comments](#pinning-comments)
- [Viewing pinned comments](#viewing-pinned-comments)
- [Unpin pinned comments](#unpin-pinned-comments)
- [Toggle feature to view resolved comments](#toggle-feature-to-view-resolved-comments)


## Adding comments

Every graph has a tab named `Graph Visualization`, on opening this tab we can see a side panel on the right side of the graph. To add a comment we have to click on the `Add comment` button as shown in the image:

![Graph Visualization Tab](_static/images/graph-page/comments/gs-screenshot-visualization-tab.png)

On clicking this button, the user will be redirected to a separate panel consisting of a `Comment box` where the user can select the part of the graph he/she wants to comment on and type the comment message in the space provided and click on the `Submit` button to create a comment.

The gif below shows an example of `Adding a new comment` to the graph.
![Add Comment Graph](_static/gifs/comments/gs-screenshot-adding-comments.gif)

**Permissions**
1) Any user having permission to access the graph can add a comment on the graph.
2) User must have an account to comment on a graph (User must be signed in).

## Viewing comments

1) Every graph has a tab named `Graph Visualization`, on opening this tab we can see a side panel on the right side of the graph.
2) If there are many comments associated with a graph, it would be difficult for the user to scroll down to see the list of all comments. **Pagination** functionality has been added to display atmost 3 comments per page.
3) To view the comment we have to click on the `View comments` button as shown in the image:

![Graph Visualization Tab](_static/images/graph-page/comments/gs-screenshot-visualization-tab.png)

On clicking this button, the user will be redirected to a separate panel where all the comments under the graph are listed down.

The gif below shows an example of `Viewing comments` of a graph.
![View Comments Graph](_static/gifs/comments/gs-screenshot-viewing-comments.gif)

**Permissions**
1) Any user having permission to access the graph can view comments of that graph.

## Replying to comments

1) For replying to a specific comment user has to click on the space provided below for a `Comment` showing `Reply..`.
2) Then the user has to enter the reply message and click on the `Reply` button. The user has to click on `Cancel` button if he/she wants to discard the reply.

![Reply Comment Gif](_static/gifs/comments/gs-screenshot-replying-to-comments.gif)

**Permissions**
1) Any user having permission to access the graph can add a comment on the graph.
2) User must have an account to comment on a graph (User must be signed in).

## Real-time experience of add and reply to comments

Since comment-system provides real-time experience using `Web-sockets` the following gifs demonstrate the real-time functionality of adding comments and replying to comments.

![Real Time Experience Add Reply Gif](_static/gifs/comments/gs-screenshot-real-time-experience-of-add-and-reply-to-comments.gif)

## Editing comments

User can edit comment messages by clicking on the `icon` present in the top-right corner of the comment box and clicking on `Edit` option. After that the user can enter the new message and click on `Edit` button to update the comment message.

![Edit Comment Gif](_static/gifs/comments/gs-screenshot-editing-comments.gif)

**Permissions**
1)  Only the creator of the comment can edit the comment message.

## Resolving comments

1) User can resolve comments by clicking on the `icon` present in the top-right corner of the comment box and clicking on `Resolve` option. After that the comments would be resolved and replies to that comment are **disabled**.
2) Only the **top most** comment in a comment thread can be resolved and the other comments in the thread(replies to top most comment) cannot be resolved.

![Resolve Comment Gif](_static/gifs/comments/gs-screenshot-resolving-comments.gif)

**Permissions**
1)  Only the creator of the comment can resolve the comment.

## Deleting comments

1) User can delete comments/replies by clicking on the `icon` present in the top-right corner of the comment/reply box and clicking on `Delete` option.
2) After a `Delete operation` the comment/reply will be **permanently lost** and cannot be retrieved.

![Delete Comment Gif](_static/gifs/comments/gs-screenshot-deleting-comments.gif)

**Permissions**
1)  Only the creator of the comment/reply can delete the comment/reply.

## Re-opening resolved comments

1) User can re-open comments by clicking on the icon present in the top-right corner of the comment box and clicking on `Re-open` option.
2) Only the **resolved comments** can be re-opened and replies are again allowed on re-opened comments.

![Re-open Comment Gif](_static/gifs/comments/gs-screenshot-re-opening-resolved-comments.gif)

**Permissions**
1) Any user having permission to access the graph can re-open a comment.

## Real-time experience of edit resolve reopen and delete comments

All the real-time functionality involving editing, resolving, deleting and re-opening the comments is demonstrated in the gif below.

![Real Time Experience Edit Resolve Reopen Delete Gif](_static/gifs/comments/gs-screenshot-real-time-experience-of-edit-resolve-reopen-and-delete-comments.gif)

## Displaying comments associated with selected graph

1) User has the ability to filter comments to view only the comments related to a graph by clicking on the radio button `View comments related to selected graph`.
2) User has to select the part of the graph on which he wishes to view the comments and the comments related to that part of the graph are listed down.

![Display Comments on Selected Graph Gif](_static/gifs/comments/gs-screenshot-displaying-comments-associated-with-selected-graph.gif)

**Permissions**
1) Any user having permission to access the graph can use this feature. 
2) User must have an account to access this feature. (User must be signed in).

## Highlighting subgraph associated with a comment

1) User can view the part of the graph a comment is associated with, this can be done by `hovering` over a comment box.
2) On hovering over a comment the part of the graph related to that comment is **highlighted**.

![Highlight Graph Gif](_static/gifs/comments/gs-screenshot-highlighting-subgraph-associated-with-a-comment.gif)

**Permissions**
1) Any user having permission to access the graph can use this feature. 
2) User must have an account to access this feature (User must be signed in).

## Pinning comments

1) Similar to **bookmarks** in browsers sometimes a user might want to **pin** comments and visit or deal with them again later.
2) For pinning comments user has to click on the `icon` present in the top-right corner of the comment box and click on `Pin` option.

![Pin Comment Gif](_static/gifs/comments/gs-screenshot-pinning-comments.gif)

**Permissions**
1) Any user having permission to access the graph can pin comments.
2) User must have an account to pin comments (User must be signed in).

## Viewing pinned comments

1) After pinning comments a user can see the list of all pinned comments by clicking on the radio button named `View pinned comments` which will display the list of all pinned comments.

![View Pinned Comments Gif](_static/gifs/comments/gs-screenshot-viewing-pinned-comments.gif)

**Permissions**
1) Any user having permission to access the graph can view his/her pinned comments.
2) User must have an account to view pinned comments (User must be signed in).

## Unpin pinned comments

1) A user can unpin a comment by clicking on the `icon` present in the top-right corner of the comment box and click on `Unpin` option.
2) On clicking this option the comment will be removed from the list of pinned comments.

![Unpin Comment Gif](_static/gifs/comments/gs-screenshot-unpin-pinned-comments.gif)

**Permissions**
1) Any user having permission to access the graph can unpin his/her pinned comments.
2) User must have an account to view unpin pinned comments (User must be signed in).

## Toggle feature to view resolved comments

1) A user can may want to see resolved or ignore them sometimes.
2) **Toggling** over the button named `Include resolved comments` in current page will help in including and ignoring the resolved comments on that particular page.

![Toggle feature Resolved Gif](_static/gifs/comments/gs-screenshot-toggle-feature-to-view-resolved-comments.gif)

**Permissions**
1) Any user having permission to access the graph to access this feature.
2) User must have an account to access this feature (User must be signed in).