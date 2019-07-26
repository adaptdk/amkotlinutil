[amkotlinutil](../../index.md) / [dk.adaptmobile.amkotlinutil.extensions](../index.md) / [android.view.View](index.md) / [showPopupMenu](./show-popup-menu.md)

# showPopupMenu

`fun `[`View`](https://developer.android.com/reference/android/view/View.html)`.showPopupMenu(items: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`PopupMenuItem`](../-popup-menu-item/index.md)`>, anchor: `[`View`](https://developer.android.com/reference/android/view/View.html)` = this, gravity: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)` = Gravity.NO_GRAVITY, @StyleRes style: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)` = 0, itemSelected: (item: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`) -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) [(source)](https://github.com/adaptmobile-organization/amkotlinutil/tree/master/amkotlinutil/src/main/java/dk/adaptmobile/amkotlinutil/extensions/ViewExtensions.kt#L330)

Extension function to show a PopupMenu on a view. Optionally, pass in a separate anchor view, if you want the popup to be centered on a different view than the clicked one

### Parameters

`items` - List of items to be shown in the PopupMenu. Description is the text to be shown in the popup, value is the text(value) that will be returned when the item is selected

`anchor` - Optional anchor view. Defaults to the clicked view.

`style` - Optional Style resource to style the popupmenu

`gravity` - Gravity flag to control gravity, defaults to NO_GRAVITY

`itemSelected` - Callback lambda with the selected value