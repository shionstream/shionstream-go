# V1CommentsGet200ResponseDataInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | 
**AnimeId** | **string** |  | 
**EpisodeId** | **string** |  | 
**UserId** | Pointer to **string** |  | [optional] 
**GuestName** | Pointer to **string** |  | [optional] 
**ParentId** | Pointer to **string** |  | [optional] 
**Content** | **string** |  | 
**IsSpoiler** | **bool** |  | 
**CreatedAt** | **string** |  | 
**UpdatedAt** | **string** |  | 
**Likes** | **float32** |  | 
**Dislikes** | **float32** |  | 

## Methods

### NewV1CommentsGet200ResponseDataInner

`func NewV1CommentsGet200ResponseDataInner(id string, animeId string, episodeId string, content string, isSpoiler bool, createdAt string, updatedAt string, likes float32, dislikes float32, ) *V1CommentsGet200ResponseDataInner`

NewV1CommentsGet200ResponseDataInner instantiates a new V1CommentsGet200ResponseDataInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1CommentsGet200ResponseDataInnerWithDefaults

`func NewV1CommentsGet200ResponseDataInnerWithDefaults() *V1CommentsGet200ResponseDataInner`

NewV1CommentsGet200ResponseDataInnerWithDefaults instantiates a new V1CommentsGet200ResponseDataInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *V1CommentsGet200ResponseDataInner) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *V1CommentsGet200ResponseDataInner) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *V1CommentsGet200ResponseDataInner) SetId(v string)`

SetId sets Id field to given value.


### GetAnimeId

`func (o *V1CommentsGet200ResponseDataInner) GetAnimeId() string`

GetAnimeId returns the AnimeId field if non-nil, zero value otherwise.

### GetAnimeIdOk

`func (o *V1CommentsGet200ResponseDataInner) GetAnimeIdOk() (*string, bool)`

GetAnimeIdOk returns a tuple with the AnimeId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAnimeId

`func (o *V1CommentsGet200ResponseDataInner) SetAnimeId(v string)`

SetAnimeId sets AnimeId field to given value.


### GetEpisodeId

`func (o *V1CommentsGet200ResponseDataInner) GetEpisodeId() string`

GetEpisodeId returns the EpisodeId field if non-nil, zero value otherwise.

### GetEpisodeIdOk

`func (o *V1CommentsGet200ResponseDataInner) GetEpisodeIdOk() (*string, bool)`

GetEpisodeIdOk returns a tuple with the EpisodeId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEpisodeId

`func (o *V1CommentsGet200ResponseDataInner) SetEpisodeId(v string)`

SetEpisodeId sets EpisodeId field to given value.


### GetUserId

`func (o *V1CommentsGet200ResponseDataInner) GetUserId() string`

GetUserId returns the UserId field if non-nil, zero value otherwise.

### GetUserIdOk

`func (o *V1CommentsGet200ResponseDataInner) GetUserIdOk() (*string, bool)`

GetUserIdOk returns a tuple with the UserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserId

`func (o *V1CommentsGet200ResponseDataInner) SetUserId(v string)`

SetUserId sets UserId field to given value.

### HasUserId

`func (o *V1CommentsGet200ResponseDataInner) HasUserId() bool`

HasUserId returns a boolean if a field has been set.

### GetGuestName

`func (o *V1CommentsGet200ResponseDataInner) GetGuestName() string`

GetGuestName returns the GuestName field if non-nil, zero value otherwise.

### GetGuestNameOk

`func (o *V1CommentsGet200ResponseDataInner) GetGuestNameOk() (*string, bool)`

GetGuestNameOk returns a tuple with the GuestName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGuestName

`func (o *V1CommentsGet200ResponseDataInner) SetGuestName(v string)`

SetGuestName sets GuestName field to given value.

### HasGuestName

`func (o *V1CommentsGet200ResponseDataInner) HasGuestName() bool`

HasGuestName returns a boolean if a field has been set.

### GetParentId

`func (o *V1CommentsGet200ResponseDataInner) GetParentId() string`

GetParentId returns the ParentId field if non-nil, zero value otherwise.

### GetParentIdOk

`func (o *V1CommentsGet200ResponseDataInner) GetParentIdOk() (*string, bool)`

GetParentIdOk returns a tuple with the ParentId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParentId

`func (o *V1CommentsGet200ResponseDataInner) SetParentId(v string)`

SetParentId sets ParentId field to given value.

### HasParentId

`func (o *V1CommentsGet200ResponseDataInner) HasParentId() bool`

HasParentId returns a boolean if a field has been set.

### GetContent

`func (o *V1CommentsGet200ResponseDataInner) GetContent() string`

GetContent returns the Content field if non-nil, zero value otherwise.

### GetContentOk

`func (o *V1CommentsGet200ResponseDataInner) GetContentOk() (*string, bool)`

GetContentOk returns a tuple with the Content field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContent

`func (o *V1CommentsGet200ResponseDataInner) SetContent(v string)`

SetContent sets Content field to given value.


### GetIsSpoiler

`func (o *V1CommentsGet200ResponseDataInner) GetIsSpoiler() bool`

GetIsSpoiler returns the IsSpoiler field if non-nil, zero value otherwise.

### GetIsSpoilerOk

`func (o *V1CommentsGet200ResponseDataInner) GetIsSpoilerOk() (*bool, bool)`

GetIsSpoilerOk returns a tuple with the IsSpoiler field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsSpoiler

`func (o *V1CommentsGet200ResponseDataInner) SetIsSpoiler(v bool)`

SetIsSpoiler sets IsSpoiler field to given value.


### GetCreatedAt

`func (o *V1CommentsGet200ResponseDataInner) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *V1CommentsGet200ResponseDataInner) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *V1CommentsGet200ResponseDataInner) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.


### GetUpdatedAt

`func (o *V1CommentsGet200ResponseDataInner) GetUpdatedAt() string`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *V1CommentsGet200ResponseDataInner) GetUpdatedAtOk() (*string, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *V1CommentsGet200ResponseDataInner) SetUpdatedAt(v string)`

SetUpdatedAt sets UpdatedAt field to given value.


### GetLikes

`func (o *V1CommentsGet200ResponseDataInner) GetLikes() float32`

GetLikes returns the Likes field if non-nil, zero value otherwise.

### GetLikesOk

`func (o *V1CommentsGet200ResponseDataInner) GetLikesOk() (*float32, bool)`

GetLikesOk returns a tuple with the Likes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLikes

`func (o *V1CommentsGet200ResponseDataInner) SetLikes(v float32)`

SetLikes sets Likes field to given value.


### GetDislikes

`func (o *V1CommentsGet200ResponseDataInner) GetDislikes() float32`

GetDislikes returns the Dislikes field if non-nil, zero value otherwise.

### GetDislikesOk

`func (o *V1CommentsGet200ResponseDataInner) GetDislikesOk() (*float32, bool)`

GetDislikesOk returns a tuple with the Dislikes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDislikes

`func (o *V1CommentsGet200ResponseDataInner) SetDislikes(v float32)`

SetDislikes sets Dislikes field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


