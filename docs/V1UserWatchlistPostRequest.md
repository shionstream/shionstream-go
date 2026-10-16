# V1UserWatchlistPostRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AnimeId** | **string** |  | 
**Status** | Pointer to **string** |  | [optional] [default to "plan_to_watch"]

## Methods

### NewV1UserWatchlistPostRequest

`func NewV1UserWatchlistPostRequest(animeId string, ) *V1UserWatchlistPostRequest`

NewV1UserWatchlistPostRequest instantiates a new V1UserWatchlistPostRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1UserWatchlistPostRequestWithDefaults

`func NewV1UserWatchlistPostRequestWithDefaults() *V1UserWatchlistPostRequest`

NewV1UserWatchlistPostRequestWithDefaults instantiates a new V1UserWatchlistPostRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAnimeId

`func (o *V1UserWatchlistPostRequest) GetAnimeId() string`

GetAnimeId returns the AnimeId field if non-nil, zero value otherwise.

### GetAnimeIdOk

`func (o *V1UserWatchlistPostRequest) GetAnimeIdOk() (*string, bool)`

GetAnimeIdOk returns a tuple with the AnimeId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAnimeId

`func (o *V1UserWatchlistPostRequest) SetAnimeId(v string)`

SetAnimeId sets AnimeId field to given value.


### GetStatus

`func (o *V1UserWatchlistPostRequest) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *V1UserWatchlistPostRequest) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *V1UserWatchlistPostRequest) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *V1UserWatchlistPostRequest) HasStatus() bool`

HasStatus returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


