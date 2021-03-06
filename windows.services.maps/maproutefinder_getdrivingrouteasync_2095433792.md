---
-api-id: M:Windows.Services.Maps.MapRouteFinder.GetDrivingRouteAsync(Windows.Devices.Geolocation.Geopoint,Windows.Devices.Geolocation.Geopoint,Windows.Services.Maps.MapRouteOptimization,Windows.Services.Maps.MapRouteRestrictions,System.Double)
-api-type: winrt method
---

<!-- Method syntax
public Windows.Foundation.IAsyncOperation<Windows.Services.Maps.MapRouteFinderResult> GetDrivingRouteAsync(Windows.Devices.Geolocation.Geopoint startPoint, Windows.Devices.Geolocation.Geopoint endPoint, Windows.Services.Maps.MapRouteOptimization optimization, Windows.Services.Maps.MapRouteRestrictions restrictions, System.Double headingInDegrees)
-->

# Windows.Services.Maps.MapRouteFinder.GetDrivingRouteAsync

## -description
Gets a driving route for the specified start and end coordinates (using optimizations, restrictions, and heading).

## -parameters
### -param startPoint
The starting point of the driving route.

### -param endPoint
The ending point of the driving route.

### -param optimization
The optimizations to apply when calculating the driving route.

### -param restrictions
The restrictions to apply when calculating the driving route.

### -param headingInDegrees
The preferred start direction from the current location for the driving route.

## -returns
When this method completes successfully, it returns a driving route contained in the [MapRouteFinderResult](maproutefinderresult.md).

## -remarks

## -examples

## -see-also
[Display  routes and directions on a map](/windows/uwp/maps-and-location/routes-and-directions), [GetDrivingRouteAsync(Geopoint, Geopoint)](maproutefinder_getdrivingrouteasync_1041948120.md), [GetDrivingRouteAsync(Geopoint, Geopoint, MapRouteOptimization)](maproutefinder_getdrivingrouteasync_1322598624.md), [GetDrivingRouteAsync(Geopoint, Geopoint, MapRouteOptimization, MapRouteRestrictions)](maproutefinder_getdrivingrouteasync_1850077408.md)
