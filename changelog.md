#9.0.0
* Release compatible with Angular 9

#9.0.1
* General improvements: removed useless components and used components from @angular/material instead.
* Solved theming issues, now it behaves correctly with any Material theme (prebuilt, or even custom! 😁)
* Completed demo page 

#9.0.2
* Version bump to fix travis badge and changelog

#9.0.3
* Resolved an annoying behaviour when using *ngIf on ngx-mat-timepicker directive (but not on the component). 
* Improved period select appearance in ngx-mat-timepicker-field
* Fixed arrows appearance in ngx-mat-timepicker-field
* Removed strict tipe checking on Input "format" allowing to pass in the form `format="24` instead of `[format]="24"`
* Improved demo

#9.0.4
* Improved UI for screens up to 360px

#9.0.5
* Fixed issue with `build --prod`
* Refactored horrible things in ngx-mat-timepicker-append-to-input.directive

#9.1.0 (deprecated)
* Now using ts-luxon instead of luxon, for best compatibility

#9.1.1
* Fixed peer dependencies

#10.0.0
* Upgrade for Angular 10

#10.0.1
* Fix appendToInput option
* Fix #11 demo page + readme
* Moved ts-luxon in dependencies

#10.0.2
* Removed console

#10.0.3
* Fixed #9: missing dependency

#10.0.4
* Upgraded ts-luxon version (fixes [#51](https://github.com/tonysamperi/ngx-mat-timepicker/issues/56))
* Fixed appearance of picker header when keyboard input is enabled
* Added coerceBooleanProperty on keyboardInputEnabled input
* Refactored timepicker adapter (performance boost)
