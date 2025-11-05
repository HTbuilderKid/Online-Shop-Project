5. It works as expected, but there is a small problem in the logic. The comment says that the rating should be between 1 and 5, inclusive, which means that it shouldn't ever be 0 or 5+. However, the line return rating < 0 || rating > 5; makes it so that putting a rating of 0 is possible.

9. No, it will not work correctly without any comments for the item. We are using an iterator to go over the comments list, so if the comments list is empty, the line Comment best = it.next(); will throw a NoSuchElementException at runtime.

10. Yes, all tests should pass now, whether positive or negative
