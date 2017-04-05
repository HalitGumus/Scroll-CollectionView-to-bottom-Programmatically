# Scroll-CollectionView-to-bottom-Programmatically
Swift 3, CollectionView, Scroll


let x = yourArray.count - 1

let y = NSIndexPath(item: x, section: 0)

collectionView.scrollToItem(at: y as IndexPath, at: .bottom, animated: true)

OR

collectionView.contentOffset.y = (400)

self.collectionView.scrollToItemAtIndexPath(NSIndexPath(forItem: yourArray.count, inSection: 0), atScrollPosition: .Bottom, animated: true)
