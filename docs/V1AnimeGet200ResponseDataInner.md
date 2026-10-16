# V1AnimeGet200ResponseDataInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | 
**Slug** | **string** |  | 
**TitleRomaji** | **string** |  | 
**TitleEnglish** | Pointer to **string** |  | [optional] 
**TitleJapanese** | Pointer to **string** |  | [optional] 
**Synopsis** | Pointer to **string** |  | [optional] 
**CoverImage** | Pointer to **string** |  | [optional] 
**BannerImage** | Pointer to **string** |  | [optional] 
**Type** | **string** |  | 
**Status** | **string** |  | 
**SeasonName** | Pointer to **string** |  | [optional] 
**SeasonYear** | Pointer to **float32** |  | [optional] 
**EpisodesCount** | **float32** |  | 
**DurationPerEp** | Pointer to **string** |  | [optional] 
**Rating** | Pointer to **float32** |  | [optional] 
**IsFeatured** | **bool** |  | 
**IsTrending** | **bool** |  | 
**SubOrDub** | **string** |  | 

## Methods

### NewV1AnimeGet200ResponseDataInner

`func NewV1AnimeGet200ResponseDataInner(id string, slug string, titleRomaji string, type_ string, status string, episodesCount float32, isFeatured bool, isTrending bool, subOrDub string, ) *V1AnimeGet200ResponseDataInner`

NewV1AnimeGet200ResponseDataInner instantiates a new V1AnimeGet200ResponseDataInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1AnimeGet200ResponseDataInnerWithDefaults

`func NewV1AnimeGet200ResponseDataInnerWithDefaults() *V1AnimeGet200ResponseDataInner`

NewV1AnimeGet200ResponseDataInnerWithDefaults instantiates a new V1AnimeGet200ResponseDataInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *V1AnimeGet200ResponseDataInner) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *V1AnimeGet200ResponseDataInner) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *V1AnimeGet200ResponseDataInner) SetId(v string)`

SetId sets Id field to given value.


### GetSlug

`func (o *V1AnimeGet200ResponseDataInner) GetSlug() string`

GetSlug returns the Slug field if non-nil, zero value otherwise.

### GetSlugOk

`func (o *V1AnimeGet200ResponseDataInner) GetSlugOk() (*string, bool)`

GetSlugOk returns a tuple with the Slug field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSlug

`func (o *V1AnimeGet200ResponseDataInner) SetSlug(v string)`

SetSlug sets Slug field to given value.


### GetTitleRomaji

`func (o *V1AnimeGet200ResponseDataInner) GetTitleRomaji() string`

GetTitleRomaji returns the TitleRomaji field if non-nil, zero value otherwise.

### GetTitleRomajiOk

`func (o *V1AnimeGet200ResponseDataInner) GetTitleRomajiOk() (*string, bool)`

GetTitleRomajiOk returns a tuple with the TitleRomaji field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitleRomaji

`func (o *V1AnimeGet200ResponseDataInner) SetTitleRomaji(v string)`

SetTitleRomaji sets TitleRomaji field to given value.


### GetTitleEnglish

`func (o *V1AnimeGet200ResponseDataInner) GetTitleEnglish() string`

GetTitleEnglish returns the TitleEnglish field if non-nil, zero value otherwise.

### GetTitleEnglishOk

`func (o *V1AnimeGet200ResponseDataInner) GetTitleEnglishOk() (*string, bool)`

GetTitleEnglishOk returns a tuple with the TitleEnglish field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitleEnglish

`func (o *V1AnimeGet200ResponseDataInner) SetTitleEnglish(v string)`

SetTitleEnglish sets TitleEnglish field to given value.

### HasTitleEnglish

`func (o *V1AnimeGet200ResponseDataInner) HasTitleEnglish() bool`

HasTitleEnglish returns a boolean if a field has been set.

### GetTitleJapanese

`func (o *V1AnimeGet200ResponseDataInner) GetTitleJapanese() string`

GetTitleJapanese returns the TitleJapanese field if non-nil, zero value otherwise.

### GetTitleJapaneseOk

`func (o *V1AnimeGet200ResponseDataInner) GetTitleJapaneseOk() (*string, bool)`

GetTitleJapaneseOk returns a tuple with the TitleJapanese field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitleJapanese

`func (o *V1AnimeGet200ResponseDataInner) SetTitleJapanese(v string)`

SetTitleJapanese sets TitleJapanese field to given value.

### HasTitleJapanese

`func (o *V1AnimeGet200ResponseDataInner) HasTitleJapanese() bool`

HasTitleJapanese returns a boolean if a field has been set.

### GetSynopsis

`func (o *V1AnimeGet200ResponseDataInner) GetSynopsis() string`

GetSynopsis returns the Synopsis field if non-nil, zero value otherwise.

### GetSynopsisOk

`func (o *V1AnimeGet200ResponseDataInner) GetSynopsisOk() (*string, bool)`

GetSynopsisOk returns a tuple with the Synopsis field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSynopsis

`func (o *V1AnimeGet200ResponseDataInner) SetSynopsis(v string)`

SetSynopsis sets Synopsis field to given value.

### HasSynopsis

`func (o *V1AnimeGet200ResponseDataInner) HasSynopsis() bool`

HasSynopsis returns a boolean if a field has been set.

### GetCoverImage

`func (o *V1AnimeGet200ResponseDataInner) GetCoverImage() string`

GetCoverImage returns the CoverImage field if non-nil, zero value otherwise.

### GetCoverImageOk

`func (o *V1AnimeGet200ResponseDataInner) GetCoverImageOk() (*string, bool)`

GetCoverImageOk returns a tuple with the CoverImage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCoverImage

`func (o *V1AnimeGet200ResponseDataInner) SetCoverImage(v string)`

SetCoverImage sets CoverImage field to given value.

### HasCoverImage

`func (o *V1AnimeGet200ResponseDataInner) HasCoverImage() bool`

HasCoverImage returns a boolean if a field has been set.

### GetBannerImage

`func (o *V1AnimeGet200ResponseDataInner) GetBannerImage() string`

GetBannerImage returns the BannerImage field if non-nil, zero value otherwise.

### GetBannerImageOk

`func (o *V1AnimeGet200ResponseDataInner) GetBannerImageOk() (*string, bool)`

GetBannerImageOk returns a tuple with the BannerImage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBannerImage

`func (o *V1AnimeGet200ResponseDataInner) SetBannerImage(v string)`

SetBannerImage sets BannerImage field to given value.

### HasBannerImage

`func (o *V1AnimeGet200ResponseDataInner) HasBannerImage() bool`

HasBannerImage returns a boolean if a field has been set.

### GetType

`func (o *V1AnimeGet200ResponseDataInner) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *V1AnimeGet200ResponseDataInner) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *V1AnimeGet200ResponseDataInner) SetType(v string)`

SetType sets Type field to given value.


### GetStatus

`func (o *V1AnimeGet200ResponseDataInner) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *V1AnimeGet200ResponseDataInner) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *V1AnimeGet200ResponseDataInner) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetSeasonName

`func (o *V1AnimeGet200ResponseDataInner) GetSeasonName() string`

GetSeasonName returns the SeasonName field if non-nil, zero value otherwise.

### GetSeasonNameOk

`func (o *V1AnimeGet200ResponseDataInner) GetSeasonNameOk() (*string, bool)`

GetSeasonNameOk returns a tuple with the SeasonName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSeasonName

`func (o *V1AnimeGet200ResponseDataInner) SetSeasonName(v string)`

SetSeasonName sets SeasonName field to given value.

### HasSeasonName

`func (o *V1AnimeGet200ResponseDataInner) HasSeasonName() bool`

HasSeasonName returns a boolean if a field has been set.

### GetSeasonYear

`func (o *V1AnimeGet200ResponseDataInner) GetSeasonYear() float32`

GetSeasonYear returns the SeasonYear field if non-nil, zero value otherwise.

### GetSeasonYearOk

`func (o *V1AnimeGet200ResponseDataInner) GetSeasonYearOk() (*float32, bool)`

GetSeasonYearOk returns a tuple with the SeasonYear field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSeasonYear

`func (o *V1AnimeGet200ResponseDataInner) SetSeasonYear(v float32)`

SetSeasonYear sets SeasonYear field to given value.

### HasSeasonYear

`func (o *V1AnimeGet200ResponseDataInner) HasSeasonYear() bool`

HasSeasonYear returns a boolean if a field has been set.

### GetEpisodesCount

`func (o *V1AnimeGet200ResponseDataInner) GetEpisodesCount() float32`

GetEpisodesCount returns the EpisodesCount field if non-nil, zero value otherwise.

### GetEpisodesCountOk

`func (o *V1AnimeGet200ResponseDataInner) GetEpisodesCountOk() (*float32, bool)`

GetEpisodesCountOk returns a tuple with the EpisodesCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEpisodesCount

`func (o *V1AnimeGet200ResponseDataInner) SetEpisodesCount(v float32)`

SetEpisodesCount sets EpisodesCount field to given value.


### GetDurationPerEp

`func (o *V1AnimeGet200ResponseDataInner) GetDurationPerEp() string`

GetDurationPerEp returns the DurationPerEp field if non-nil, zero value otherwise.

### GetDurationPerEpOk

`func (o *V1AnimeGet200ResponseDataInner) GetDurationPerEpOk() (*string, bool)`

GetDurationPerEpOk returns a tuple with the DurationPerEp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDurationPerEp

`func (o *V1AnimeGet200ResponseDataInner) SetDurationPerEp(v string)`

SetDurationPerEp sets DurationPerEp field to given value.

### HasDurationPerEp

`func (o *V1AnimeGet200ResponseDataInner) HasDurationPerEp() bool`

HasDurationPerEp returns a boolean if a field has been set.

### GetRating

`func (o *V1AnimeGet200ResponseDataInner) GetRating() float32`

GetRating returns the Rating field if non-nil, zero value otherwise.

### GetRatingOk

`func (o *V1AnimeGet200ResponseDataInner) GetRatingOk() (*float32, bool)`

GetRatingOk returns a tuple with the Rating field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRating

`func (o *V1AnimeGet200ResponseDataInner) SetRating(v float32)`

SetRating sets Rating field to given value.

### HasRating

`func (o *V1AnimeGet200ResponseDataInner) HasRating() bool`

HasRating returns a boolean if a field has been set.

### GetIsFeatured

`func (o *V1AnimeGet200ResponseDataInner) GetIsFeatured() bool`

GetIsFeatured returns the IsFeatured field if non-nil, zero value otherwise.

### GetIsFeaturedOk

`func (o *V1AnimeGet200ResponseDataInner) GetIsFeaturedOk() (*bool, bool)`

GetIsFeaturedOk returns a tuple with the IsFeatured field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsFeatured

`func (o *V1AnimeGet200ResponseDataInner) SetIsFeatured(v bool)`

SetIsFeatured sets IsFeatured field to given value.


### GetIsTrending

`func (o *V1AnimeGet200ResponseDataInner) GetIsTrending() bool`

GetIsTrending returns the IsTrending field if non-nil, zero value otherwise.

### GetIsTrendingOk

`func (o *V1AnimeGet200ResponseDataInner) GetIsTrendingOk() (*bool, bool)`

GetIsTrendingOk returns a tuple with the IsTrending field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsTrending

`func (o *V1AnimeGet200ResponseDataInner) SetIsTrending(v bool)`

SetIsTrending sets IsTrending field to given value.


### GetSubOrDub

`func (o *V1AnimeGet200ResponseDataInner) GetSubOrDub() string`

GetSubOrDub returns the SubOrDub field if non-nil, zero value otherwise.

### GetSubOrDubOk

`func (o *V1AnimeGet200ResponseDataInner) GetSubOrDubOk() (*string, bool)`

GetSubOrDubOk returns a tuple with the SubOrDub field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubOrDub

`func (o *V1AnimeGet200ResponseDataInner) SetSubOrDub(v string)`

SetSubOrDub sets SubOrDub field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


