# \UserAPI

All URIs are relative to *https://api.gox.my.id*

Method | HTTP request | Description
------------- | ------------- | -------------
[**V1UserHistoryDelete**](UserAPI.md#V1UserHistoryDelete) | **Delete** /v1/user/history | Clear All History
[**V1UserHistoryGet**](UserAPI.md#V1UserHistoryGet) | **Get** /v1/user/history | Get Watch History
[**V1UserHistoryIdDelete**](UserAPI.md#V1UserHistoryIdDelete) | **Delete** /v1/user/history/{id} | Delete History Item
[**V1UserHistoryPost**](UserAPI.md#V1UserHistoryPost) | **Post** /v1/user/history | Record Playback Progress
[**V1UserProfileGet**](UserAPI.md#V1UserProfileGet) | **Get** /v1/user/profile | Get User Profile
[**V1UserSettingsGet**](UserAPI.md#V1UserSettingsGet) | **Get** /v1/user/settings | Get User Settings
[**V1UserSettingsPatch**](UserAPI.md#V1UserSettingsPatch) | **Patch** /v1/user/settings | Update User Settings
[**V1UserWatchlistAnimeIdDelete**](UserAPI.md#V1UserWatchlistAnimeIdDelete) | **Delete** /v1/user/watchlist/{animeId} | Remove from Watchlist
[**V1UserWatchlistAnimeIdPatch**](UserAPI.md#V1UserWatchlistAnimeIdPatch) | **Patch** /v1/user/watchlist/{animeId} | Update Watchlist Entry
[**V1UserWatchlistGet**](UserAPI.md#V1UserWatchlistGet) | **Get** /v1/user/watchlist | Get User Watchlist
[**V1UserWatchlistPost**](UserAPI.md#V1UserWatchlistPost) | **Post** /v1/user/watchlist | Add to Watchlist



## V1UserHistoryDelete

> V1UserSettingsPatch200Response V1UserHistoryDelete(ctx).Execute()

Clear All History



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/shionstream/shionstream-go"
)

func main() {

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.UserAPI.V1UserHistoryDelete(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UserAPI.V1UserHistoryDelete``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1UserHistoryDelete`: V1UserSettingsPatch200Response
	fmt.Fprintf(os.Stdout, "Response from `UserAPI.V1UserHistoryDelete`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiV1UserHistoryDeleteRequest struct via the builder pattern


### Return type

[**V1UserSettingsPatch200Response**](V1UserSettingsPatch200Response.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1UserHistoryGet

> V1UserHistoryGet200Response V1UserHistoryGet(ctx).Limit(limit).Execute()

Get Watch History



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/shionstream/shionstream-go"
)

func main() {
	limit := "limit_example" // string |  (optional) (default to "50")

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.UserAPI.V1UserHistoryGet(context.Background()).Limit(limit).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UserAPI.V1UserHistoryGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1UserHistoryGet`: V1UserHistoryGet200Response
	fmt.Fprintf(os.Stdout, "Response from `UserAPI.V1UserHistoryGet`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiV1UserHistoryGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **limit** | **string** |  | [default to &quot;50&quot;]

### Return type

[**V1UserHistoryGet200Response**](V1UserHistoryGet200Response.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1UserHistoryIdDelete

> V1UserSettingsPatch200Response V1UserHistoryIdDelete(ctx, id).Execute()

Delete History Item



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/shionstream/shionstream-go"
)

func main() {
	id := "id_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.UserAPI.V1UserHistoryIdDelete(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UserAPI.V1UserHistoryIdDelete``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1UserHistoryIdDelete`: V1UserSettingsPatch200Response
	fmt.Fprintf(os.Stdout, "Response from `UserAPI.V1UserHistoryIdDelete`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1UserHistoryIdDeleteRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**V1UserSettingsPatch200Response**](V1UserSettingsPatch200Response.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1UserHistoryPost

> V1UserSettingsPatch200Response V1UserHistoryPost(ctx).V1UserHistoryPostRequest(v1UserHistoryPostRequest).Execute()

Record Playback Progress



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/shionstream/shionstream-go"
)

func main() {
	v1UserHistoryPostRequest := *openapiclient.NewV1UserHistoryPostRequest("AnimeId_example", "EpisodeId_example") // V1UserHistoryPostRequest |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.UserAPI.V1UserHistoryPost(context.Background()).V1UserHistoryPostRequest(v1UserHistoryPostRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UserAPI.V1UserHistoryPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1UserHistoryPost`: V1UserSettingsPatch200Response
	fmt.Fprintf(os.Stdout, "Response from `UserAPI.V1UserHistoryPost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiV1UserHistoryPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **v1UserHistoryPostRequest** | [**V1UserHistoryPostRequest**](V1UserHistoryPostRequest.md) |  | 

### Return type

[**V1UserSettingsPatch200Response**](V1UserSettingsPatch200Response.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1UserProfileGet

> V1UserProfileGet200Response V1UserProfileGet(ctx).Execute()

Get User Profile



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/shionstream/shionstream-go"
)

func main() {

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.UserAPI.V1UserProfileGet(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UserAPI.V1UserProfileGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1UserProfileGet`: V1UserProfileGet200Response
	fmt.Fprintf(os.Stdout, "Response from `UserAPI.V1UserProfileGet`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiV1UserProfileGetRequest struct via the builder pattern


### Return type

[**V1UserProfileGet200Response**](V1UserProfileGet200Response.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1UserSettingsGet

> V1UserSettingsGet200Response V1UserSettingsGet(ctx).Execute()

Get User Settings



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/shionstream/shionstream-go"
)

func main() {

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.UserAPI.V1UserSettingsGet(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UserAPI.V1UserSettingsGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1UserSettingsGet`: V1UserSettingsGet200Response
	fmt.Fprintf(os.Stdout, "Response from `UserAPI.V1UserSettingsGet`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiV1UserSettingsGetRequest struct via the builder pattern


### Return type

[**V1UserSettingsGet200Response**](V1UserSettingsGet200Response.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1UserSettingsPatch

> V1UserSettingsPatch200Response V1UserSettingsPatch(ctx).V1UserSettingsPatchRequest(v1UserSettingsPatchRequest).Execute()

Update User Settings



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/shionstream/shionstream-go"
)

func main() {
	v1UserSettingsPatchRequest := *openapiclient.NewV1UserSettingsPatchRequest() // V1UserSettingsPatchRequest |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.UserAPI.V1UserSettingsPatch(context.Background()).V1UserSettingsPatchRequest(v1UserSettingsPatchRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UserAPI.V1UserSettingsPatch``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1UserSettingsPatch`: V1UserSettingsPatch200Response
	fmt.Fprintf(os.Stdout, "Response from `UserAPI.V1UserSettingsPatch`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiV1UserSettingsPatchRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **v1UserSettingsPatchRequest** | [**V1UserSettingsPatchRequest**](V1UserSettingsPatchRequest.md) |  | 

### Return type

[**V1UserSettingsPatch200Response**](V1UserSettingsPatch200Response.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1UserWatchlistAnimeIdDelete

> V1UserSettingsPatch200Response V1UserWatchlistAnimeIdDelete(ctx, animeId).Execute()

Remove from Watchlist



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/shionstream/shionstream-go"
)

func main() {
	animeId := "animeId_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.UserAPI.V1UserWatchlistAnimeIdDelete(context.Background(), animeId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UserAPI.V1UserWatchlistAnimeIdDelete``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1UserWatchlistAnimeIdDelete`: V1UserSettingsPatch200Response
	fmt.Fprintf(os.Stdout, "Response from `UserAPI.V1UserWatchlistAnimeIdDelete`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**animeId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1UserWatchlistAnimeIdDeleteRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**V1UserSettingsPatch200Response**](V1UserSettingsPatch200Response.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1UserWatchlistAnimeIdPatch

> V1UserSettingsPatch200Response V1UserWatchlistAnimeIdPatch(ctx, animeId).V1UserWatchlistAnimeIdPatchRequest(v1UserWatchlistAnimeIdPatchRequest).Execute()

Update Watchlist Entry



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/shionstream/shionstream-go"
)

func main() {
	animeId := "animeId_example" // string | 
	v1UserWatchlistAnimeIdPatchRequest := *openapiclient.NewV1UserWatchlistAnimeIdPatchRequest() // V1UserWatchlistAnimeIdPatchRequest |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.UserAPI.V1UserWatchlistAnimeIdPatch(context.Background(), animeId).V1UserWatchlistAnimeIdPatchRequest(v1UserWatchlistAnimeIdPatchRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UserAPI.V1UserWatchlistAnimeIdPatch``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1UserWatchlistAnimeIdPatch`: V1UserSettingsPatch200Response
	fmt.Fprintf(os.Stdout, "Response from `UserAPI.V1UserWatchlistAnimeIdPatch`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**animeId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1UserWatchlistAnimeIdPatchRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **v1UserWatchlistAnimeIdPatchRequest** | [**V1UserWatchlistAnimeIdPatchRequest**](V1UserWatchlistAnimeIdPatchRequest.md) |  | 

### Return type

[**V1UserSettingsPatch200Response**](V1UserSettingsPatch200Response.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1UserWatchlistGet

> V1UserWatchlistGet200Response V1UserWatchlistGet(ctx).Status(status).Execute()

Get User Watchlist



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/shionstream/shionstream-go"
)

func main() {
	status := "status_example" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.UserAPI.V1UserWatchlistGet(context.Background()).Status(status).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UserAPI.V1UserWatchlistGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1UserWatchlistGet`: V1UserWatchlistGet200Response
	fmt.Fprintf(os.Stdout, "Response from `UserAPI.V1UserWatchlistGet`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiV1UserWatchlistGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **status** | **string** |  | 

### Return type

[**V1UserWatchlistGet200Response**](V1UserWatchlistGet200Response.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1UserWatchlistPost

> V1UserSettingsPatch200Response V1UserWatchlistPost(ctx).V1UserWatchlistPostRequest(v1UserWatchlistPostRequest).Execute()

Add to Watchlist



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/shionstream/shionstream-go"
)

func main() {
	v1UserWatchlistPostRequest := *openapiclient.NewV1UserWatchlistPostRequest("AnimeId_example") // V1UserWatchlistPostRequest |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.UserAPI.V1UserWatchlistPost(context.Background()).V1UserWatchlistPostRequest(v1UserWatchlistPostRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UserAPI.V1UserWatchlistPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1UserWatchlistPost`: V1UserSettingsPatch200Response
	fmt.Fprintf(os.Stdout, "Response from `UserAPI.V1UserWatchlistPost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiV1UserWatchlistPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **v1UserWatchlistPostRequest** | [**V1UserWatchlistPostRequest**](V1UserWatchlistPostRequest.md) |  | 

### Return type

[**V1UserSettingsPatch200Response**](V1UserSettingsPatch200Response.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

