# V1AnimeSlugGet200ResponseData

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
**Genres** | [**[]V1AnimeSlugGet200ResponseDataGenresInner**](V1AnimeSlugGet200ResponseDataGenresInner.md) |  | 
**Studios** | [**[]V1AnimeSlugGet200ResponseDataGenresInner**](V1AnimeSlugGet200ResponseDataGenresInner.md) |  | 
**Schedule** | Pointer to [**V1AnimeSlugGet200ResponseDataSchedule**](V1AnimeSlugGet200ResponseDataSchedule.md) |  | [optional] 
**TrendingStats** | Pointer to [**V1AnimeSlugGet200ResponseDataTrendingStats**](V1AnimeSlugGet200ResponseDataTrendingStats.md) |  | [optional] 

## Methods

### NewV1AnimeSlugGet200ResponseData

`func NewV1AnimeSlugGet200ResponseData(id string, slug string, titleRomaji string, type_ string, status string, episodesCount float32, isFeatured bool, isTrending bool, subOrDub string, genres []V1AnimeSlugGet200ResponseDataGenresInner, studios []V1AnimeSlugGet200ResponseDataGenresInner, ) *V1AnimeSlugGet200ResponseData`

NewV1AnimeSlugGet200ResponseData instantiates a new V1AnimeSlugGet200ResponseData object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1AnimeSlugGet200ResponseDataWithDefaults

`func NewV1AnimeSlugGet200ResponseDataWithDefaults() *V1AnimeSlugGet200ResponseData`

NewV1AnimeSlugGet200ResponseDataWithDefaults instantiates a new V1AnimeSlugGet200ResponseData object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *V1AnimeSlugGet200ResponseData) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *V1AnimeSlugGet200ResponseData) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *V1AnimeSlugGet200ResponseData) SetId(v string)`

SetId sets Id field to given value.


### GetSlug

`func (o *V1AnimeSlugGet200ResponseData) GetSlug() string`

GetSlug returns the Slug field if non-nil, zero value otherwise.

### GetSlugOk

`func (o *V1AnimeSlugGet200ResponseData) GetSlugOk() (*string, bool)`

GetSlugOk returns a tuple with the Slug field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSlug

`func (o *V1AnimeSlugGet200ResponseData) SetSlug(v string)`

SetSlug sets Slug field to given value.


### GetTitleRomaji

`func (o *V1AnimeSlugGet200ResponseData) GetTitleRomaji() string`

GetTitleRomaji returns the TitleRomaji field if non-nil, zero value otherwise.

### GetTitleRomajiOk

`func (o *V1AnimeSlugGet200ResponseData) GetTitleRomajiOk() (*string, bool)`

GetTitleRomajiOk returns a tuple with the TitleRomaji field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitleRomaji

`func (o *V1AnimeSlugGet200ResponseData) SetTitleRomaji(v string)`

SetTitleRomaji sets TitleRomaji field to given value.


### GetTitleEnglish

`func (o *V1AnimeSlugGet200ResponseData) GetTitleEnglish() string`

GetTitleEnglish returns the TitleEnglish field if non-nil, zero value otherwise.

### GetTitleEnglishOk

`func (o *V1AnimeSlugGet200ResponseData) GetTitleEnglishOk() (*string, bool)`

GetTitleEnglishOk returns a tuple with the TitleEnglish field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitleEnglish

`func (o *V1AnimeSlugGet200ResponseData) SetTitleEnglish(v string)`

SetTitleEnglish sets TitleEnglish field to given value.

### HasTitleEnglish

`func (o *V1AnimeSlugGet200ResponseData) HasTitleEnglish() bool`

HasTitleEnglish returns a boolean if a field has been set.

### GetTitleJapanese

`func (o *V1AnimeSlugGet200ResponseData) GetTitleJapanese() string`

GetTitleJapanese returns the TitleJapanese field if non-nil, zero value otherwise.

### GetTitleJapaneseOk

`func (o *V1AnimeSlugGet200ResponseData) GetTitleJapaneseOk() (*string, bool)`

GetTitleJapaneseOk returns a tuple with the TitleJapanese field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitleJapanese

`func (o *V1AnimeSlugGet200ResponseData) SetTitleJapanese(v string)`

SetTitleJapanese sets TitleJapanese field to given value.

### HasTitleJapanese

`func (o *V1AnimeSlugGet200ResponseData) HasTitleJapanese() bool`

HasTitleJapanese returns a boolean if a field has been set.

### GetSynopsis

`func (o *V1AnimeSlugGet200ResponseData) GetSynopsis() string`

GetSynopsis returns the Synopsis field if non-nil, zero value otherwise.

### GetSynopsisOk

`func (o *V1AnimeSlugGet200ResponseData) GetSynopsisOk() (*string, bool)`

GetSynopsisOk returns a tuple with the Synopsis field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSynopsis

`func (o *V1AnimeSlugGet200ResponseData) SetSynopsis(v string)`

SetSynopsis sets Synopsis field to given value.

### HasSynopsis

`func (o *V1AnimeSlugGet200ResponseData) HasSynopsis() bool`

HasSynopsis returns a boolean if a field has been set.

### GetCoverImage

`func (o *V1AnimeSlugGet200ResponseData) GetCoverImage() string`

GetCoverImage returns the CoverImage field if non-nil, zero value otherwise.

### GetCoverImageOk

`func (o *V1AnimeSlugGet200ResponseData) GetCoverImageOk() (*string, bool)`

GetCoverImageOk returns a tuple with the CoverImage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCoverImage

`func (o *V1AnimeSlugGet200ResponseData) SetCoverImage(v string)`

SetCoverImage sets CoverImage field to given value.

### HasCoverImage

`func (o *V1AnimeSlugGet200ResponseData) HasCoverImage() bool`

HasCoverImage returns a boolean if a field has been set.

### GetBannerImage

`func (o *V1AnimeSlugGet200ResponseData) GetBannerImage() string`

GetBannerImage returns the BannerImage field if non-nil, zero value otherwise.

### GetBannerImageOk

`func (o *V1AnimeSlugGet200ResponseData) GetBannerImageOk() (*string, bool)`

GetBannerImageOk returns a tuple with the BannerImage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBannerImage

`func (o *V1AnimeSlugGet200ResponseData) SetBannerImage(v string)`

SetBannerImage sets BannerImage field to given value.

### HasBannerImage

`func (o *V1AnimeSlugGet200ResponseData) HasBannerImage() bool`

HasBannerImage returns a boolean if a field has been set.

### GetType

`func (o *V1AnimeSlugGet200ResponseData) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *V1AnimeSlugGet200ResponseData) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *V1AnimeSlugGet200ResponseData) SetType(v string)`

SetType sets Type field to given value.


### GetStatus

`func (o *V1AnimeSlugGet200ResponseData) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *V1AnimeSlugGet200ResponseData) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *V1AnimeSlugGet200ResponseData) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetSeasonName

`func (o *V1AnimeSlugGet200ResponseData) GetSeasonName() string`

GetSeasonName returns the SeasonName field if non-nil, zero value otherwise.

### GetSeasonNameOk

`func (o *V1AnimeSlugGet200ResponseData) GetSeasonNameOk() (*string, bool)`

GetSeasonNameOk returns a tuple with the SeasonName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSeasonName

`func (o *V1AnimeSlugGet200ResponseData) SetSeasonName(v string)`

SetSeasonName sets SeasonName field to given value.

### HasSeasonName

`func (o *V1AnimeSlugGet200ResponseData) HasSeasonName() bool`

HasSeasonName returns a boolean if a field has been set.

### GetSeasonYear

`func (o *V1AnimeSlugGet200ResponseData) GetSeasonYear() float32`

GetSeasonYear returns the SeasonYear field if non-nil, zero value otherwise.

### GetSeasonYearOk

`func (o *V1AnimeSlugGet200ResponseData) GetSeasonYearOk() (*float32, bool)`

GetSeasonYearOk returns a tuple with the SeasonYear field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSeasonYear

`func (o *V1AnimeSlugGet200ResponseData) SetSeasonYear(v float32)`

SetSeasonYear sets SeasonYear field to given value.

### HasSeasonYear

`func (o *V1AnimeSlugGet200ResponseData) HasSeasonYear() bool`

HasSeasonYear returns a boolean if a field has been set.

### GetEpisodesCount

`func (o *V1AnimeSlugGet200ResponseData) GetEpisodesCount() float32`

GetEpisodesCount returns the EpisodesCount field if non-nil, zero value otherwise.

### GetEpisodesCountOk

`func (o *V1AnimeSlugGet200ResponseData) GetEpisodesCountOk() (*float32, bool)`

GetEpisodesCountOk returns a tuple with the EpisodesCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEpisodesCount

`func (o *V1AnimeSlugGet200ResponseData) SetEpisodesCount(v float32)`

SetEpisodesCount sets EpisodesCount field to given value.


### GetDurationPerEp

`func (o *V1AnimeSlugGet200ResponseData) GetDurationPerEp() string`

GetDurationPerEp returns the DurationPerEp field if non-nil, zero value otherwise.

### GetDurationPerEpOk

`func (o *V1AnimeSlugGet200ResponseData) GetDurationPerEpOk() (*string, bool)`

GetDurationPerEpOk returns a tuple with the DurationPerEp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDurationPerEp

`func (o *V1AnimeSlugGet200ResponseData) SetDurationPerEp(v string)`

SetDurationPerEp sets DurationPerEp field to given value.

### HasDurationPerEp

`func (o *V1AnimeSlugGet200ResponseData) HasDurationPerEp() bool`

HasDurationPerEp returns a boolean if a field has been set.

### GetRating

`func (o *V1AnimeSlugGet200ResponseData) GetRating() float32`

GetRating returns the Rating field if non-nil, zero value otherwise.

### GetRatingOk

`func (o *V1AnimeSlugGet200ResponseData) GetRatingOk() (*float32, bool)`

GetRatingOk returns a tuple with the Rating field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRating

`func (o *V1AnimeSlugGet200ResponseData) SetRating(v float32)`

SetRating sets Rating field to given value.

### HasRating

`func (o *V1AnimeSlugGet200ResponseData) HasRating() bool`

HasRating returns a boolean if a field has been set.

### GetIsFeatured

`func (o *V1AnimeSlugGet200ResponseData) GetIsFeatured() bool`

GetIsFeatured returns the IsFeatured field if non-nil, zero value otherwise.

### GetIsFeaturedOk

`func (o *V1AnimeSlugGet200ResponseData) GetIsFeaturedOk() (*bool, bool)`

GetIsFeaturedOk returns a tuple with the IsFeatured field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsFeatured

`func (o *V1AnimeSlugGet200ResponseData) SetIsFeatured(v bool)`

SetIsFeatured sets IsFeatured field to given value.


### GetIsTrending

`func (o *V1AnimeSlugGet200ResponseData) GetIsTrending() bool`

GetIsTrending returns the IsTrending field if non-nil, zero value otherwise.

### GetIsTrendingOk

`func (o *V1AnimeSlugGet200ResponseData) GetIsTrendingOk() (*bool, bool)`

GetIsTrendingOk returns a tuple with the IsTrending field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsTrending

`func (o *V1AnimeSlugGet200ResponseData) SetIsTrending(v bool)`

SetIsTrending sets IsTrending field to given value.


### GetSubOrDub

`func (o *V1AnimeSlugGet200ResponseData) GetSubOrDub() string`

GetSubOrDub returns the SubOrDub field if non-nil, zero value otherwise.

### GetSubOrDubOk

`func (o *V1AnimeSlugGet200ResponseData) GetSubOrDubOk() (*string, bool)`

GetSubOrDubOk returns a tuple with the SubOrDub field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubOrDub

`func (o *V1AnimeSlugGet200ResponseData) SetSubOrDub(v string)`

SetSubOrDub sets SubOrDub field to given value.


### GetGenres

`func (o *V1AnimeSlugGet200ResponseData) GetGenres() []V1AnimeSlugGet200ResponseDataGenresInner`

GetGenres returns the Genres field if non-nil, zero value otherwise.

### GetGenresOk

`func (o *V1AnimeSlugGet200ResponseData) GetGenresOk() (*[]V1AnimeSlugGet200ResponseDataGenresInner, bool)`

GetGenresOk returns a tuple with the Genres field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGenres

`func (o *V1AnimeSlugGet200ResponseData) SetGenres(v []V1AnimeSlugGet200ResponseDataGenresInner)`

SetGenres sets Genres field to given value.


### GetStudios

`func (o *V1AnimeSlugGet200ResponseData) GetStudios() []V1AnimeSlugGet200ResponseDataGenresInner`

GetStudios returns the Studios field if non-nil, zero value otherwise.

### GetStudiosOk

`func (o *V1AnimeSlugGet200ResponseData) GetStudiosOk() (*[]V1AnimeSlugGet200ResponseDataGenresInner, bool)`

GetStudiosOk returns a tuple with the Studios field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStudios

`func (o *V1AnimeSlugGet200ResponseData) SetStudios(v []V1AnimeSlugGet200ResponseDataGenresInner)`

SetStudios sets Studios field to given value.


### GetSchedule

`func (o *V1AnimeSlugGet200ResponseData) GetSchedule() V1AnimeSlugGet200ResponseDataSchedule`

GetSchedule returns the Schedule field if non-nil, zero value otherwise.

### GetScheduleOk

`func (o *V1AnimeSlugGet200ResponseData) GetScheduleOk() (*V1AnimeSlugGet200ResponseDataSchedule, bool)`

GetScheduleOk returns a tuple with the Schedule field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSchedule

`func (o *V1AnimeSlugGet200ResponseData) SetSchedule(v V1AnimeSlugGet200ResponseDataSchedule)`

SetSchedule sets Schedule field to given value.

### HasSchedule

`func (o *V1AnimeSlugGet200ResponseData) HasSchedule() bool`

HasSchedule returns a boolean if a field has been set.

### GetTrendingStats

`func (o *V1AnimeSlugGet200ResponseData) GetTrendingStats() V1AnimeSlugGet200ResponseDataTrendingStats`

GetTrendingStats returns the TrendingStats field if non-nil, zero value otherwise.

### GetTrendingStatsOk

`func (o *V1AnimeSlugGet200ResponseData) GetTrendingStatsOk() (*V1AnimeSlugGet200ResponseDataTrendingStats, bool)`

GetTrendingStatsOk returns a tuple with the TrendingStats field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrendingStats

`func (o *V1AnimeSlugGet200ResponseData) SetTrendingStats(v V1AnimeSlugGet200ResponseDataTrendingStats)`

SetTrendingStats sets TrendingStats field to given value.

### HasTrendingStats

`func (o *V1AnimeSlugGet200ResponseData) HasTrendingStats() bool`

HasTrendingStats returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


