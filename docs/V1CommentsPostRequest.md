# V1CommentsPostRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AnimeId** | **string** |  | 
**EpisodeId** | **string** |  | 
**Content** | **string** |  | 
**ParentId** | Pointer to **string** |  | [optional] 
**IsSpoiler** | Pointer to **bool** |  | [optional] [default to false]
**GuestName** | Pointer to **string** |  | [optional] 
**GuestEmail** | Pointer to **string** |  | [optional] 

## Methods

### NewV1CommentsPostRequest

`func NewV1CommentsPostRequest(animeId string, episodeId string, content string, ) *V1CommentsPostRequest`

NewV1CommentsPostRequest instantiates a new V1CommentsPostRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1CommentsPostRequestWithDefaults

`func NewV1CommentsPostRequestWithDefaults() *V1CommentsPostRequest`

NewV1CommentsPostRequestWithDefaults instantiates a new V1CommentsPostRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAnimeId

`func (o *V1CommentsPostRequest) GetAnimeId() string`

GetAnimeId returns the AnimeId field if non-nil, zero value otherwise.

### GetAnimeIdOk

`func (o *V1CommentsPostRequest) GetAnimeIdOk() (*string, bool)`

GetAnimeIdOk returns a tuple with the AnimeId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAnimeId

`func (o *V1CommentsPostRequest) SetAnimeId(v string)`

SetAnimeId sets AnimeId field to given value.


### GetEpisodeId

`func (o *V1CommentsPostRequest) GetEpisodeId() string`

GetEpisodeId returns the EpisodeId field if non-nil, zero value otherwise.

### GetEpisodeIdOk

`func (o *V1CommentsPostRequest) GetEpisodeIdOk() (*string, bool)`

GetEpisodeIdOk returns a tuple with the EpisodeId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEpisodeId

`func (o *V1CommentsPostRequest) SetEpisodeId(v string)`

SetEpisodeId sets EpisodeId field to given value.


### GetContent

`func (o *V1CommentsPostRequest) GetContent() string`

GetContent returns the Content field if non-nil, zero value otherwise.

### GetContentOk

`func (o *V1CommentsPostRequest) GetContentOk() (*string, bool)`

GetContentOk returns a tuple with the Content field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContent

`func (o *V1CommentsPostRequest) SetContent(v string)`

SetContent sets Content field to given value.


### GetParentId

`func (o *V1CommentsPostRequest) GetParentId() string`

GetParentId returns the ParentId field if non-nil, zero value otherwise.

### GetParentIdOk

`func (o *V1CommentsPostRequest) GetParentIdOk() (*string, bool)`

GetParentIdOk returns a tuple with the ParentId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParentId

`func (o *V1CommentsPostRequest) SetParentId(v string)`

SetParentId sets ParentId field to given value.

### HasParentId

`func (o *V1CommentsPostRequest) HasParentId() bool`

HasParentId returns a boolean if a field has been set.

### GetIsSpoiler

`func (o *V1CommentsPostRequest) GetIsSpoiler() bool`

GetIsSpoiler returns the IsSpoiler field if non-nil, zero value otherwise.

### GetIsSpoilerOk

`func (o *V1CommentsPostRequest) GetIsSpoilerOk() (*bool, bool)`

GetIsSpoilerOk returns a tuple with the IsSpoiler field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsSpoiler

`func (o *V1CommentsPostRequest) SetIsSpoiler(v bool)`

SetIsSpoiler sets IsSpoiler field to given value.

### HasIsSpoiler

`func (o *V1CommentsPostRequest) HasIsSpoiler() bool`

HasIsSpoiler returns a boolean if a field has been set.

### GetGuestName

`func (o *V1CommentsPostRequest) GetGuestName() string`

GetGuestName returns the GuestName field if non-nil, zero value otherwise.

### GetGuestNameOk

`func (o *V1CommentsPostRequest) GetGuestNameOk() (*string, bool)`

GetGuestNameOk returns a tuple with the GuestName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGuestName

`func (o *V1CommentsPostRequest) SetGuestName(v string)`

SetGuestName sets GuestName field to given value.

### HasGuestName

`func (o *V1CommentsPostRequest) HasGuestName() bool`

HasGuestName returns a boolean if a field has been set.

### GetGuestEmail

`func (o *V1CommentsPostRequest) GetGuestEmail() string`

GetGuestEmail returns the GuestEmail field if non-nil, zero value otherwise.

### GetGuestEmailOk

`func (o *V1CommentsPostRequest) GetGuestEmailOk() (*string, bool)`

GetGuestEmailOk returns a tuple with the GuestEmail field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGuestEmail

`func (o *V1CommentsPostRequest) SetGuestEmail(v string)`

SetGuestEmail sets GuestEmail field to given value.

### HasGuestEmail

`func (o *V1CommentsPostRequest) HasGuestEmail() bool`

HasGuestEmail returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


