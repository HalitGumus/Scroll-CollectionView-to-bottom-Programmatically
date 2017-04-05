# Scroll-CollectionView-to-bottom-Programmatically
Swift 3, CollectionView, Scroll


collectionView.contentOffset.y = (400)

self.collectionView.scrollToItemAtIndexPath(NSIndexPath(forItem: yourArray.count, inSection: 0), atScrollPosition: .Bottom, animated: true)
