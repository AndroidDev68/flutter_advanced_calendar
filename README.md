# flutter_advanced_calendar

An advanced calendar provides a rich API for widget customization that opens a new look and feel in your app.

## Advanced Calendar Theme LAF
| Advanced Calendar Light Theme | Advanced Calendar Dark Theme |
|:-:|:-:|
| ![PREVIEW_LIGHT_COLLAPSED](./PREVIEW_LIGHT_COLLAPSED.png) | ![PREVIEW_DARK_COLLAPSED](./PREVIEW_DARK_COLLAPSED.png) |
| ![PREVIEW_LIGHT_EXPANDED](./PREVIEW_LIGHT_EXPANDED.png) | ![PREVIEW_DARK_EXPANDED](./PREVIEW_DARK_EXPANDED.png) |


## Examples

Regular Calendar

```dart
final _controller = AdvancedCalendarController.today();
// ...
AdvancedCalendar(
    controller: _controller,
)
// ...
```

Custom Date Calendar

```dart
final _controller = AdvancedCalendarController.custom(DateTime(2021, 2, 15));
// ...
AdvancedCalendar(
    controller: _controller,
)
// ...
```

## AdvancedCalendar Parameters
|Parameter|Description|Type|Default|
|:--------|:----------|:---|:------|
|`controller`|Controller that manage calendar state|*AdvancedCalendarController*|required|
|`weekLineHeight`|Height of week line|*double*|32.0|
|`preloadMonthViewAmount`|Amount of months in month view to preload|*int*|13|
|`preloadWeekViewAmount`|Amount of weeks in week view to preload|*int*|21|
|`weeksInMonthViewAmount`|Weeks lines amount in month view|*int*|6|