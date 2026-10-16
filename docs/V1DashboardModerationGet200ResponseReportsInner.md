# V1DashboardModerationGet200ResponseReportsInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | 
**CommentId** | **string** |  | 
**CommentText** | **string** |  | 
**AnimeTitle** | **string** |  | 
**EpisodeNumber** | **float32** |  | 
**Author** | [**V1DashboardModerationGet200ResponseReportsInnerAuthor**](V1DashboardModerationGet200ResponseReportsInnerAuthor.md) |  | 
**Reporter** | [**V1DashboardModerationGet200ResponseReportsInnerReporter**](V1DashboardModerationGet200ResponseReportsInnerReporter.md) |  | 
**Reason** | **string** |  | 
**Status** | **string** |  | 
**ReportedAt** | **string** |  | 
**FlaggedBySystem** | **bool** |  | 

## Methods

### NewV1DashboardModerationGet200ResponseReportsInner

`func NewV1DashboardModerationGet200ResponseReportsInner(id string, commentId string, commentText string, animeTitle string, episodeNumber float32, author V1DashboardModerationGet200ResponseReportsInnerAuthor, reporter V1DashboardModerationGet200ResponseReportsInnerReporter, reason string, status string, reportedAt string, flaggedBySystem bool, ) *V1DashboardModerationGet200ResponseReportsInner`

NewV1DashboardModerationGet200ResponseReportsInner instantiates a new V1DashboardModerationGet200ResponseReportsInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1DashboardModerationGet200ResponseReportsInnerWithDefaults

`func NewV1DashboardModerationGet200ResponseReportsInnerWithDefaults() *V1DashboardModerationGet200ResponseReportsInner`

NewV1DashboardModerationGet200ResponseReportsInnerWithDefaults instantiates a new V1DashboardModerationGet200ResponseReportsInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *V1DashboardModerationGet200ResponseReportsInner) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *V1DashboardModerationGet200ResponseReportsInner) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *V1DashboardModerationGet200ResponseReportsInner) SetId(v string)`

SetId sets Id field to given value.


### GetCommentId

`func (o *V1DashboardModerationGet200ResponseReportsInner) GetCommentId() string`

GetCommentId returns the CommentId field if non-nil, zero value otherwise.

### GetCommentIdOk

`func (o *V1DashboardModerationGet200ResponseReportsInner) GetCommentIdOk() (*string, bool)`

GetCommentIdOk returns a tuple with the CommentId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCommentId

`func (o *V1DashboardModerationGet200ResponseReportsInner) SetCommentId(v string)`

SetCommentId sets CommentId field to given value.


### GetCommentText

`func (o *V1DashboardModerationGet200ResponseReportsInner) GetCommentText() string`

GetCommentText returns the CommentText field if non-nil, zero value otherwise.

### GetCommentTextOk

`func (o *V1DashboardModerationGet200ResponseReportsInner) GetCommentTextOk() (*string, bool)`

GetCommentTextOk returns a tuple with the CommentText field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCommentText

`func (o *V1DashboardModerationGet200ResponseReportsInner) SetCommentText(v string)`

SetCommentText sets CommentText field to given value.


### GetAnimeTitle

`func (o *V1DashboardModerationGet200ResponseReportsInner) GetAnimeTitle() string`

GetAnimeTitle returns the AnimeTitle field if non-nil, zero value otherwise.

### GetAnimeTitleOk

`func (o *V1DashboardModerationGet200ResponseReportsInner) GetAnimeTitleOk() (*string, bool)`

GetAnimeTitleOk returns a tuple with the AnimeTitle field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAnimeTitle

`func (o *V1DashboardModerationGet200ResponseReportsInner) SetAnimeTitle(v string)`

SetAnimeTitle sets AnimeTitle field to given value.


### GetEpisodeNumber

`func (o *V1DashboardModerationGet200ResponseReportsInner) GetEpisodeNumber() float32`

GetEpisodeNumber returns the EpisodeNumber field if non-nil, zero value otherwise.

### GetEpisodeNumberOk

`func (o *V1DashboardModerationGet200ResponseReportsInner) GetEpisodeNumberOk() (*float32, bool)`

GetEpisodeNumberOk returns a tuple with the EpisodeNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEpisodeNumber

`func (o *V1DashboardModerationGet200ResponseReportsInner) SetEpisodeNumber(v float32)`

SetEpisodeNumber sets EpisodeNumber field to given value.


### GetAuthor

`func (o *V1DashboardModerationGet200ResponseReportsInner) GetAuthor() V1DashboardModerationGet200ResponseReportsInnerAuthor`

GetAuthor returns the Author field if non-nil, zero value otherwise.

### GetAuthorOk

`func (o *V1DashboardModerationGet200ResponseReportsInner) GetAuthorOk() (*V1DashboardModerationGet200ResponseReportsInnerAuthor, bool)`

GetAuthorOk returns a tuple with the Author field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAuthor

`func (o *V1DashboardModerationGet200ResponseReportsInner) SetAuthor(v V1DashboardModerationGet200ResponseReportsInnerAuthor)`

SetAuthor sets Author field to given value.


### GetReporter

`func (o *V1DashboardModerationGet200ResponseReportsInner) GetReporter() V1DashboardModerationGet200ResponseReportsInnerReporter`

GetReporter returns the Reporter field if non-nil, zero value otherwise.

### GetReporterOk

`func (o *V1DashboardModerationGet200ResponseReportsInner) GetReporterOk() (*V1DashboardModerationGet200ResponseReportsInnerReporter, bool)`

GetReporterOk returns a tuple with the Reporter field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReporter

`func (o *V1DashboardModerationGet200ResponseReportsInner) SetReporter(v V1DashboardModerationGet200ResponseReportsInnerReporter)`

SetReporter sets Reporter field to given value.


### GetReason

`func (o *V1DashboardModerationGet200ResponseReportsInner) GetReason() string`

GetReason returns the Reason field if non-nil, zero value otherwise.

### GetReasonOk

`func (o *V1DashboardModerationGet200ResponseReportsInner) GetReasonOk() (*string, bool)`

GetReasonOk returns a tuple with the Reason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReason

`func (o *V1DashboardModerationGet200ResponseReportsInner) SetReason(v string)`

SetReason sets Reason field to given value.


### GetStatus

`func (o *V1DashboardModerationGet200ResponseReportsInner) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *V1DashboardModerationGet200ResponseReportsInner) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *V1DashboardModerationGet200ResponseReportsInner) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetReportedAt

`func (o *V1DashboardModerationGet200ResponseReportsInner) GetReportedAt() string`

GetReportedAt returns the ReportedAt field if non-nil, zero value otherwise.

### GetReportedAtOk

`func (o *V1DashboardModerationGet200ResponseReportsInner) GetReportedAtOk() (*string, bool)`

GetReportedAtOk returns a tuple with the ReportedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReportedAt

`func (o *V1DashboardModerationGet200ResponseReportsInner) SetReportedAt(v string)`

SetReportedAt sets ReportedAt field to given value.


### GetFlaggedBySystem

`func (o *V1DashboardModerationGet200ResponseReportsInner) GetFlaggedBySystem() bool`

GetFlaggedBySystem returns the FlaggedBySystem field if non-nil, zero value otherwise.

### GetFlaggedBySystemOk

`func (o *V1DashboardModerationGet200ResponseReportsInner) GetFlaggedBySystemOk() (*bool, bool)`

GetFlaggedBySystemOk returns a tuple with the FlaggedBySystem field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFlaggedBySystem

`func (o *V1DashboardModerationGet200ResponseReportsInner) SetFlaggedBySystem(v bool)`

SetFlaggedBySystem sets FlaggedBySystem field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


