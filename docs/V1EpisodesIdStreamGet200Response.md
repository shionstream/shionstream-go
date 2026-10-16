# V1EpisodesIdStreamGet200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Success** | **bool** |  | 
**Episode** | [**V1EpisodesIdStreamGet200ResponseEpisode**](V1EpisodesIdStreamGet200ResponseEpisode.md) |  | 
**Sources** | [**[]V1EpisodesIdStreamGet200ResponseSourcesInner**](V1EpisodesIdStreamGet200ResponseSourcesInner.md) |  | 
**Subtitles** | [**[]V1EpisodesIdStreamGet200ResponseSubtitlesInner**](V1EpisodesIdStreamGet200ResponseSubtitlesInner.md) |  | 
**Audio** | [**[]V1EpisodesIdStreamGet200ResponseAudioInner**](V1EpisodesIdStreamGet200ResponseAudioInner.md) |  | 

## Methods

### NewV1EpisodesIdStreamGet200Response

`func NewV1EpisodesIdStreamGet200Response(success bool, episode V1EpisodesIdStreamGet200ResponseEpisode, sources []V1EpisodesIdStreamGet200ResponseSourcesInner, subtitles []V1EpisodesIdStreamGet200ResponseSubtitlesInner, audio []V1EpisodesIdStreamGet200ResponseAudioInner, ) *V1EpisodesIdStreamGet200Response`

NewV1EpisodesIdStreamGet200Response instantiates a new V1EpisodesIdStreamGet200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1EpisodesIdStreamGet200ResponseWithDefaults

`func NewV1EpisodesIdStreamGet200ResponseWithDefaults() *V1EpisodesIdStreamGet200Response`

NewV1EpisodesIdStreamGet200ResponseWithDefaults instantiates a new V1EpisodesIdStreamGet200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSuccess

`func (o *V1EpisodesIdStreamGet200Response) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *V1EpisodesIdStreamGet200Response) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *V1EpisodesIdStreamGet200Response) SetSuccess(v bool)`

SetSuccess sets Success field to given value.


### GetEpisode

`func (o *V1EpisodesIdStreamGet200Response) GetEpisode() V1EpisodesIdStreamGet200ResponseEpisode`

GetEpisode returns the Episode field if non-nil, zero value otherwise.

### GetEpisodeOk

`func (o *V1EpisodesIdStreamGet200Response) GetEpisodeOk() (*V1EpisodesIdStreamGet200ResponseEpisode, bool)`

GetEpisodeOk returns a tuple with the Episode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEpisode

`func (o *V1EpisodesIdStreamGet200Response) SetEpisode(v V1EpisodesIdStreamGet200ResponseEpisode)`

SetEpisode sets Episode field to given value.


### GetSources

`func (o *V1EpisodesIdStreamGet200Response) GetSources() []V1EpisodesIdStreamGet200ResponseSourcesInner`

GetSources returns the Sources field if non-nil, zero value otherwise.

### GetSourcesOk

`func (o *V1EpisodesIdStreamGet200Response) GetSourcesOk() (*[]V1EpisodesIdStreamGet200ResponseSourcesInner, bool)`

GetSourcesOk returns a tuple with the Sources field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSources

`func (o *V1EpisodesIdStreamGet200Response) SetSources(v []V1EpisodesIdStreamGet200ResponseSourcesInner)`

SetSources sets Sources field to given value.


### GetSubtitles

`func (o *V1EpisodesIdStreamGet200Response) GetSubtitles() []V1EpisodesIdStreamGet200ResponseSubtitlesInner`

GetSubtitles returns the Subtitles field if non-nil, zero value otherwise.

### GetSubtitlesOk

`func (o *V1EpisodesIdStreamGet200Response) GetSubtitlesOk() (*[]V1EpisodesIdStreamGet200ResponseSubtitlesInner, bool)`

GetSubtitlesOk returns a tuple with the Subtitles field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubtitles

`func (o *V1EpisodesIdStreamGet200Response) SetSubtitles(v []V1EpisodesIdStreamGet200ResponseSubtitlesInner)`

SetSubtitles sets Subtitles field to given value.


### GetAudio

`func (o *V1EpisodesIdStreamGet200Response) GetAudio() []V1EpisodesIdStreamGet200ResponseAudioInner`

GetAudio returns the Audio field if non-nil, zero value otherwise.

### GetAudioOk

`func (o *V1EpisodesIdStreamGet200Response) GetAudioOk() (*[]V1EpisodesIdStreamGet200ResponseAudioInner, bool)`

GetAudioOk returns a tuple with the Audio field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAudio

`func (o *V1EpisodesIdStreamGet200Response) SetAudio(v []V1EpisodesIdStreamGet200ResponseAudioInner)`

SetAudio sets Audio field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


