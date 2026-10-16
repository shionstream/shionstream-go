# V1UserHistoryPostRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AnimeId** | **string** |  | 
**EpisodeId** | **string** |  | 
**EpisodeNumber** | Pointer to **float32** |  | [optional] 
**ProgressPercent** | Pointer to **float32** |  | [optional] [default to 0]
**DurationSeconds** | Pointer to **float32** |  | [optional] [default to 0]
**ProgressSeconds** | Pointer to **float32** |  | [optional] [default to 0]

## Methods

### NewV1UserHistoryPostRequest

`func NewV1UserHistoryPostRequest(animeId string, episodeId string, ) *V1UserHistoryPostRequest`

NewV1UserHistoryPostRequest instantiates a new V1UserHistoryPostRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1UserHistoryPostRequestWithDefaults

`func NewV1UserHistoryPostRequestWithDefaults() *V1UserHistoryPostRequest`

NewV1UserHistoryPostRequestWithDefaults instantiates a new V1UserHistoryPostRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAnimeId

`func (o *V1UserHistoryPostRequest) GetAnimeId() string`

GetAnimeId returns the AnimeId field if non-nil, zero value otherwise.

### GetAnimeIdOk

`func (o *V1UserHistoryPostRequest) GetAnimeIdOk() (*string, bool)`

GetAnimeIdOk returns a tuple with the AnimeId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAnimeId

`func (o *V1UserHistoryPostRequest) SetAnimeId(v string)`

SetAnimeId sets AnimeId field to given value.


### GetEpisodeId

`func (o *V1UserHistoryPostRequest) GetEpisodeId() string`

GetEpisodeId returns the EpisodeId field if non-nil, zero value otherwise.

### GetEpisodeIdOk

`func (o *V1UserHistoryPostRequest) GetEpisodeIdOk() (*string, bool)`

GetEpisodeIdOk returns a tuple with the EpisodeId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEpisodeId

`func (o *V1UserHistoryPostRequest) SetEpisodeId(v string)`

SetEpisodeId sets EpisodeId field to given value.


### GetEpisodeNumber

`func (o *V1UserHistoryPostRequest) GetEpisodeNumber() float32`

GetEpisodeNumber returns the EpisodeNumber field if non-nil, zero value otherwise.

### GetEpisodeNumberOk

`func (o *V1UserHistoryPostRequest) GetEpisodeNumberOk() (*float32, bool)`

GetEpisodeNumberOk returns a tuple with the EpisodeNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEpisodeNumber

`func (o *V1UserHistoryPostRequest) SetEpisodeNumber(v float32)`

SetEpisodeNumber sets EpisodeNumber field to given value.

### HasEpisodeNumber

`func (o *V1UserHistoryPostRequest) HasEpisodeNumber() bool`

HasEpisodeNumber returns a boolean if a field has been set.

### GetProgressPercent

`func (o *V1UserHistoryPostRequest) GetProgressPercent() float32`

GetProgressPercent returns the ProgressPercent field if non-nil, zero value otherwise.

### GetProgressPercentOk

`func (o *V1UserHistoryPostRequest) GetProgressPercentOk() (*float32, bool)`

GetProgressPercentOk returns a tuple with the ProgressPercent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProgressPercent

`func (o *V1UserHistoryPostRequest) SetProgressPercent(v float32)`

SetProgressPercent sets ProgressPercent field to given value.

### HasProgressPercent

`func (o *V1UserHistoryPostRequest) HasProgressPercent() bool`

HasProgressPercent returns a boolean if a field has been set.

### GetDurationSeconds

`func (o *V1UserHistoryPostRequest) GetDurationSeconds() float32`

GetDurationSeconds returns the DurationSeconds field if non-nil, zero value otherwise.

### GetDurationSecondsOk

`func (o *V1UserHistoryPostRequest) GetDurationSecondsOk() (*float32, bool)`

GetDurationSecondsOk returns a tuple with the DurationSeconds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDurationSeconds

`func (o *V1UserHistoryPostRequest) SetDurationSeconds(v float32)`

SetDurationSeconds sets DurationSeconds field to given value.

### HasDurationSeconds

`func (o *V1UserHistoryPostRequest) HasDurationSeconds() bool`

HasDurationSeconds returns a boolean if a field has been set.

### GetProgressSeconds

`func (o *V1UserHistoryPostRequest) GetProgressSeconds() float32`

GetProgressSeconds returns the ProgressSeconds field if non-nil, zero value otherwise.

### GetProgressSecondsOk

`func (o *V1UserHistoryPostRequest) GetProgressSecondsOk() (*float32, bool)`

GetProgressSecondsOk returns a tuple with the ProgressSeconds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProgressSeconds

`func (o *V1UserHistoryPostRequest) SetProgressSeconds(v float32)`

SetProgressSeconds sets ProgressSeconds field to given value.

### HasProgressSeconds

`func (o *V1UserHistoryPostRequest) HasProgressSeconds() bool`

HasProgressSeconds returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


