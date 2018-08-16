This is an example project (while I was following along with a YouTube tutorial) on how to make a thumbnail view with images that a user can scroll down (as a UICollectionView) without using a Storyboard (all code).

I'm using Swift 4.2 with Xcode 10, while following along with [this tutorial](https://www.youtube.com/watch?v=3Xv1mJvwXok).

I'm planning on using this concept on an iPhone app I'm currently working on (I'll probably need to integrate this all-code UI with my existing WYSIWYG-based Storyboard UI), but didn't want to directly start adding in work code to this project so that I could push it up to this public Github repo.

Overall, this method for creating a UI (code-based) seems a lot simpler and more powerful (as a developer who wants to precisely and uniformly place several things into a view). It is also more robust for larger teams working on the same codebase (could easily resolve potential merge conflicts, no huge RAM overhead requirement to load a storybaord file).

The complaint that this isn't the 'recommended' way by Apple, or that UI code uses a lot of redundant boilerplate code can be answered by showing how modern and CSS-like this experience is; and, if it's too boilerplate, you can simply refactor out the reptitive code blocks inside wrapper functions, as shown in this example project.

In the near future, it looks like I'll be mixing storyboard UI with code-based UI and seeing how that pans out.