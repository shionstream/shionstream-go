# Go API client for shionstream

Modular anime streaming and metadata API built with Hono on Cloudflare Workers.

## Overview
This API client was generated for ShionStream API using the OpenAPI specification.

- API version: 1.0.0
- Package version: 1.0.0
- Generator version: 7.26.0
- Build package: org.openapitools.codegen.languages.GoClientCodegen
For more information, please visit [https://gox.my.id](https://gox.my.id)

## Installation

Import the package in a go file in your project and run `go mod tidy`:

```go
import shionstream "github.com/shionstream/shionstream-go"
```

To use a proxy, set the environment variable `HTTP_PROXY`:

```go
os.Setenv("HTTP_PROXY", "http://proxy_name:proxy_port")
```

## Configuration of Server URL

Default configuration comes with `Servers` field that contains server objects as defined in the OpenAPI specification.

### Select Server Configuration

For using other server than the one defined on index 0 set context value `shionstream.ContextServerIndex` of type `int`.

```go
ctx := context.WithValue(context.Background(), shionstream.ContextServerIndex, 1)
```

### Templated Server URL

Templated server URL is formatted using default variables from configuration or from context value `shionstream.ContextServerVariables` of type `map[string]string`.

```go
ctx := context.WithValue(context.Background(), shionstream.ContextServerVariables, map[string]string{
	"basePath": "v2",
})
```

Note, enum values are always validated and all unused variables are silently ignored.

### URLs Configuration per Operation

Each operation can use different server URL defined using `OperationServers` map in the `Configuration`.
An operation is uniquely identified by `"{classname}Service.{nickname}"` string.
Similar rules for overriding default operation server index and variables applies by using `shionstream.ContextOperationServerIndices` and `shionstream.ContextOperationServerVariables` context maps.

```go
ctx := context.WithValue(context.Background(), shionstream.ContextOperationServerIndices, map[string]int{
	"{classname}Service.{nickname}": 2,
})
ctx = context.WithValue(context.Background(), shionstream.ContextOperationServerVariables, map[string]map[string]string{
	"{classname}Service.{nickname}": {
		"port": "8443",
	},
})
```

## Documentation for API Endpoints

All URIs are relative to *https://api.gox.my.id*

Class | Method | HTTP request | Description
------------ | ------------- | ------------- | -------------
*AnimeAPI* | [**V1AnimeGet**](docs/AnimeAPI.md#v1animeget) | **Get** /v1/anime | List Anime Catalog
*AnimeAPI* | [**V1AnimeSlugGet**](docs/AnimeAPI.md#v1animeslugget) | **Get** /v1/anime/{slug} | Get Anime Details by Slug
*CommentsAPI* | [**V1CommentsGet**](docs/CommentsAPI.md#v1commentsget) | **Get** /v1/comments | Get Episode Comments
*CommentsAPI* | [**V1CommentsIdLikePost**](docs/CommentsAPI.md#v1commentsidlikepost) | **Post** /v1/comments/{id}/like | Like or Dislike Comment
*CommentsAPI* | [**V1CommentsIdReportPost**](docs/CommentsAPI.md#v1commentsidreportpost) | **Post** /v1/comments/{id}/report | Report Comment
*CommentsAPI* | [**V1CommentsPost**](docs/CommentsAPI.md#v1commentspost) | **Post** /v1/comments | Create Comment
*DashboardAPI* | [**V1DashboardAnimeGet**](docs/DashboardAPI.md#v1dashboardanimeget) | **Get** /v1/dashboard/anime | Get Administrative Anime List
*DashboardAPI* | [**V1DashboardCategoriesGet**](docs/DashboardAPI.md#v1dashboardcategoriesget) | **Get** /v1/dashboard/categories | Get Category &amp; Genre Distributions
*DashboardAPI* | [**V1DashboardEpisodesGet**](docs/DashboardAPI.md#v1dashboardepisodesget) | **Get** /v1/dashboard/episodes | Get Administrative Episodes List
*DashboardAPI* | [**V1DashboardModerationGet**](docs/DashboardAPI.md#v1dashboardmoderationget) | **Get** /v1/dashboard/moderation | Get Comment Moderation Reports
*DashboardAPI* | [**V1DashboardModerationIdPatch**](docs/DashboardAPI.md#v1dashboardmoderationidpatch) | **Patch** /v1/dashboard/moderation/{id} | Resolve or Dismiss Moderation Report
*DashboardAPI* | [**V1DashboardOverviewGet**](docs/DashboardAPI.md#v1dashboardoverviewget) | **Get** /v1/dashboard/overview | Get Dashboard Overview
*DashboardAPI* | [**V1DashboardRolesGet**](docs/DashboardAPI.md#v1dashboardrolesget) | **Get** /v1/dashboard/roles | Get System Roles &amp; Permissions
*DashboardAPI* | [**V1DashboardSeasonsGet**](docs/DashboardAPI.md#v1dashboardseasonsget) | **Get** /v1/dashboard/seasons | Get Seasonal Broadcast Distributions
*DashboardAPI* | [**V1DashboardStatsGet**](docs/DashboardAPI.md#v1dashboardstatsget) | **Get** /v1/dashboard/stats | Get Platform Stats
*DashboardAPI* | [**V1DashboardUsersGet**](docs/DashboardAPI.md#v1dashboardusersget) | **Get** /v1/dashboard/users | Get Users Directory (Admin Only)
*EpisodesAPI* | [**V1AnimeSlugEpisodesGet**](docs/EpisodesAPI.md#v1animeslugepisodesget) | **Get** /v1/anime/{slug}/episodes | List Episodes by Anime Slug
*EpisodesAPI* | [**V1EpisodesIdStreamGet**](docs/EpisodesAPI.md#v1episodesidstreamget) | **Get** /v1/episodes/{id}/stream | Get Episode Stream Sources
*SampleAPI* | [**V1ProtectedSampleGet**](docs/SampleAPI.md#v1protectedsampleget) | **Get** /v1/protected/sample | Protected Sample Endpoint
*SystemAPI* | [**HealthGet**](docs/SystemAPI.md#healthget) | **Get** /health | Health Check
*UploadAPI* | [**V1UploadHlsPost**](docs/UploadAPI.md#v1uploadhlspost) | **Post** /v1/upload/hls | Upload HLS Package to Cloudflare R2
*UploadAPI* | [**V1UploadImagePost**](docs/UploadAPI.md#v1uploadimagepost) | **Post** /v1/upload/image | Upload Image to Cloudflare R2
*UserAPI* | [**V1UserHistoryDelete**](docs/UserAPI.md#v1userhistorydelete) | **Delete** /v1/user/history | Clear All History
*UserAPI* | [**V1UserHistoryGet**](docs/UserAPI.md#v1userhistoryget) | **Get** /v1/user/history | Get Watch History
*UserAPI* | [**V1UserHistoryIdDelete**](docs/UserAPI.md#v1userhistoryiddelete) | **Delete** /v1/user/history/{id} | Delete History Item
*UserAPI* | [**V1UserHistoryPost**](docs/UserAPI.md#v1userhistorypost) | **Post** /v1/user/history | Record Playback Progress
*UserAPI* | [**V1UserProfileGet**](docs/UserAPI.md#v1userprofileget) | **Get** /v1/user/profile | Get User Profile
*UserAPI* | [**V1UserSettingsGet**](docs/UserAPI.md#v1usersettingsget) | **Get** /v1/user/settings | Get User Settings
*UserAPI* | [**V1UserSettingsPatch**](docs/UserAPI.md#v1usersettingspatch) | **Patch** /v1/user/settings | Update User Settings
*UserAPI* | [**V1UserWatchlistAnimeIdDelete**](docs/UserAPI.md#v1userwatchlistanimeiddelete) | **Delete** /v1/user/watchlist/{animeId} | Remove from Watchlist
*UserAPI* | [**V1UserWatchlistAnimeIdPatch**](docs/UserAPI.md#v1userwatchlistanimeidpatch) | **Patch** /v1/user/watchlist/{animeId} | Update Watchlist Entry
*UserAPI* | [**V1UserWatchlistGet**](docs/UserAPI.md#v1userwatchlistget) | **Get** /v1/user/watchlist | Get User Watchlist
*UserAPI* | [**V1UserWatchlistPost**](docs/UserAPI.md#v1userwatchlistpost) | **Post** /v1/user/watchlist | Add to Watchlist


## Documentation For Models

 - [HealthGet200Response](docs/HealthGet200Response.md)
 - [HealthGet500Response](docs/HealthGet500Response.md)
 - [V1AnimeGet200Response](docs/V1AnimeGet200Response.md)
 - [V1AnimeGet200ResponseDataInner](docs/V1AnimeGet200ResponseDataInner.md)
 - [V1AnimeGet200ResponsePagination](docs/V1AnimeGet200ResponsePagination.md)
 - [V1AnimeSlugEpisodesGet200Response](docs/V1AnimeSlugEpisodesGet200Response.md)
 - [V1AnimeSlugEpisodesGet200ResponseAnime](docs/V1AnimeSlugEpisodesGet200ResponseAnime.md)
 - [V1AnimeSlugEpisodesGet200ResponseDataInner](docs/V1AnimeSlugEpisodesGet200ResponseDataInner.md)
 - [V1AnimeSlugGet200Response](docs/V1AnimeSlugGet200Response.md)
 - [V1AnimeSlugGet200ResponseData](docs/V1AnimeSlugGet200ResponseData.md)
 - [V1AnimeSlugGet200ResponseDataGenresInner](docs/V1AnimeSlugGet200ResponseDataGenresInner.md)
 - [V1AnimeSlugGet200ResponseDataSchedule](docs/V1AnimeSlugGet200ResponseDataSchedule.md)
 - [V1AnimeSlugGet200ResponseDataTrendingStats](docs/V1AnimeSlugGet200ResponseDataTrendingStats.md)
 - [V1CommentsGet200Response](docs/V1CommentsGet200Response.md)
 - [V1CommentsGet200ResponseDataInner](docs/V1CommentsGet200ResponseDataInner.md)
 - [V1CommentsIdLikePost200Response](docs/V1CommentsIdLikePost200Response.md)
 - [V1CommentsIdLikePostRequest](docs/V1CommentsIdLikePostRequest.md)
 - [V1CommentsIdReportPostRequest](docs/V1CommentsIdReportPostRequest.md)
 - [V1CommentsPost201Response](docs/V1CommentsPost201Response.md)
 - [V1CommentsPostRequest](docs/V1CommentsPostRequest.md)
 - [V1DashboardAnimeGet200Response](docs/V1DashboardAnimeGet200Response.md)
 - [V1DashboardCategoriesGet200Response](docs/V1DashboardCategoriesGet200Response.md)
 - [V1DashboardCategoriesGet200ResponseCategoriesInner](docs/V1DashboardCategoriesGet200ResponseCategoriesInner.md)
 - [V1DashboardCategoriesGet200ResponseGenresInner](docs/V1DashboardCategoriesGet200ResponseGenresInner.md)
 - [V1DashboardEpisodesGet200Response](docs/V1DashboardEpisodesGet200Response.md)
 - [V1DashboardModerationGet200Response](docs/V1DashboardModerationGet200Response.md)
 - [V1DashboardModerationGet200ResponseReportsInner](docs/V1DashboardModerationGet200ResponseReportsInner.md)
 - [V1DashboardModerationGet200ResponseReportsInnerAuthor](docs/V1DashboardModerationGet200ResponseReportsInnerAuthor.md)
 - [V1DashboardModerationGet200ResponseReportsInnerReporter](docs/V1DashboardModerationGet200ResponseReportsInnerReporter.md)
 - [V1DashboardModerationIdPatchRequest](docs/V1DashboardModerationIdPatchRequest.md)
 - [V1DashboardOverviewGet200Response](docs/V1DashboardOverviewGet200Response.md)
 - [V1DashboardOverviewGet200ResponseNotificationsInner](docs/V1DashboardOverviewGet200ResponseNotificationsInner.md)
 - [V1DashboardOverviewGet200ResponseRecentActivitiesInner](docs/V1DashboardOverviewGet200ResponseRecentActivitiesInner.md)
 - [V1DashboardOverviewGet200ResponseTrafficDataInner](docs/V1DashboardOverviewGet200ResponseTrafficDataInner.md)
 - [V1DashboardRolesGet200Response](docs/V1DashboardRolesGet200Response.md)
 - [V1DashboardRolesGet200ResponseRolesInner](docs/V1DashboardRolesGet200ResponseRolesInner.md)
 - [V1DashboardSeasonsGet200Response](docs/V1DashboardSeasonsGet200Response.md)
 - [V1DashboardSeasonsGet200ResponseSeasonsInner](docs/V1DashboardSeasonsGet200ResponseSeasonsInner.md)
 - [V1DashboardStatsGet200Response](docs/V1DashboardStatsGet200Response.md)
 - [V1DashboardStatsGet200ResponseStats](docs/V1DashboardStatsGet200ResponseStats.md)
 - [V1DashboardUsersGet200Response](docs/V1DashboardUsersGet200Response.md)
 - [V1DashboardUsersGet200ResponseUsersInner](docs/V1DashboardUsersGet200ResponseUsersInner.md)
 - [V1EpisodesIdStreamGet200Response](docs/V1EpisodesIdStreamGet200Response.md)
 - [V1EpisodesIdStreamGet200ResponseAudioInner](docs/V1EpisodesIdStreamGet200ResponseAudioInner.md)
 - [V1EpisodesIdStreamGet200ResponseEpisode](docs/V1EpisodesIdStreamGet200ResponseEpisode.md)
 - [V1EpisodesIdStreamGet200ResponseSourcesInner](docs/V1EpisodesIdStreamGet200ResponseSourcesInner.md)
 - [V1EpisodesIdStreamGet200ResponseSubtitlesInner](docs/V1EpisodesIdStreamGet200ResponseSubtitlesInner.md)
 - [V1ProtectedSampleGet200Response](docs/V1ProtectedSampleGet200Response.md)
 - [V1ProtectedSampleGet200ResponseUser](docs/V1ProtectedSampleGet200ResponseUser.md)
 - [V1ProtectedSampleGet401Response](docs/V1ProtectedSampleGet401Response.md)
 - [V1UploadHlsPost200Response](docs/V1UploadHlsPost200Response.md)
 - [V1UploadHlsPost200ResponseData](docs/V1UploadHlsPost200ResponseData.md)
 - [V1UploadImagePost200Response](docs/V1UploadImagePost200Response.md)
 - [V1UploadImagePost200ResponseData](docs/V1UploadImagePost200ResponseData.md)
 - [V1UserHistoryGet200Response](docs/V1UserHistoryGet200Response.md)
 - [V1UserHistoryGet200ResponseDataInner](docs/V1UserHistoryGet200ResponseDataInner.md)
 - [V1UserHistoryPostRequest](docs/V1UserHistoryPostRequest.md)
 - [V1UserProfileGet200Response](docs/V1UserProfileGet200Response.md)
 - [V1UserProfileGet200ResponseData](docs/V1UserProfileGet200ResponseData.md)
 - [V1UserProfileGet200ResponseDataActivity](docs/V1UserProfileGet200ResponseDataActivity.md)
 - [V1UserSettingsGet200Response](docs/V1UserSettingsGet200Response.md)
 - [V1UserSettingsGet200ResponseData](docs/V1UserSettingsGet200ResponseData.md)
 - [V1UserSettingsGet200ResponseDataNotifications](docs/V1UserSettingsGet200ResponseDataNotifications.md)
 - [V1UserSettingsGet200ResponseDataPlayer](docs/V1UserSettingsGet200ResponseDataPlayer.md)
 - [V1UserSettingsPatch200Response](docs/V1UserSettingsPatch200Response.md)
 - [V1UserSettingsPatchRequest](docs/V1UserSettingsPatchRequest.md)
 - [V1UserSettingsPatchRequestNotifications](docs/V1UserSettingsPatchRequestNotifications.md)
 - [V1UserSettingsPatchRequestPlayer](docs/V1UserSettingsPatchRequestPlayer.md)
 - [V1UserSettingsPatchRequestProfile](docs/V1UserSettingsPatchRequestProfile.md)
 - [V1UserWatchlistAnimeIdPatchRequest](docs/V1UserWatchlistAnimeIdPatchRequest.md)
 - [V1UserWatchlistGet200Response](docs/V1UserWatchlistGet200Response.md)
 - [V1UserWatchlistGet200ResponseDataInner](docs/V1UserWatchlistGet200ResponseDataInner.md)
 - [V1UserWatchlistPostRequest](docs/V1UserWatchlistPostRequest.md)


## Documentation For Authorization


Authentication schemes defined for the API:
### Bearer

- **Type**: HTTP Bearer token authentication

Example

```go
auth := context.WithValue(context.Background(), shionstream.ContextAccessToken, "BEARER_TOKEN_STRING")
r, err := client.Service.Operation(auth, args)
```


## Documentation for Utility Methods

Due to the fact that model structure members are all pointers, this package contains
a number of utility functions to easily obtain pointers to values of basic types.
Each of these functions takes a value of the given basic type and returns a pointer to it:

* `PtrBool`
* `PtrInt`
* `PtrInt32`
* `PtrInt64`
* `PtrFloat`
* `PtrFloat32`
* `PtrFloat64`
* `PtrString`
* `PtrTime`

## Author

dev@gox.my.id

