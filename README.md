# Google-Maps-To-Kakao-Daum-Maps
As a foreigner who has travelled to Korea before I discovered a common issue when requesting taxis and a general lack of GPS information on google maps. When searching a location there was often times an address that was useless to taxi drivers and couldn't be input into the more popular local GPS services hosted by Daum/Kakao. Using the GeoCoding API from google maps and the Kakao Developers Coordinates to Address Translation API I will be able to convert google maps addresses to addresses in Korean usable by taxi drivers and searchable in Kakao maps.

GeoCoding Request Formatting
HTTP request returns a JSON results Array we want the Geometry array within and location array element 0 = lat element 1 = long
https://developers.google.com/maps/documentation/geocoding/intro#GeocodingRequests

Getting an API key
https://developers.google.com/maps/documentation/geocoding/get-api-key

