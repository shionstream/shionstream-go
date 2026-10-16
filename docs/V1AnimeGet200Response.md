# V1AnimeGet200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Success** | **bool** |  | 
**Data** | [**[]V1AnimeGet200ResponseDataInner**](V1AnimeGet200ResponseDataInner.md) |  | 
**Pagination** | [**V1AnimeGet200ResponsePagination**](V1AnimeGet200ResponsePagination.md) |  | 

## Methods

### NewV1AnimeGet200Response

`func NewV1AnimeGet200Response(success bool, data []V1AnimeGet200ResponseDataInner, pagination V1AnimeGet200ResponsePagination, ) *V1AnimeGet200Response`

NewV1AnimeGet200Response instantiates a new V1AnimeGet200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1AnimeGet200ResponseWithDefaults

`func NewV1AnimeGet200ResponseWithDefaults() *V1AnimeGet200Response`

NewV1AnimeGet200ResponseWithDefaults instantiates a new V1AnimeGet200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSuccess

`func (o *V1AnimeGet200Response) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *V1AnimeGet200Response) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *V1AnimeGet200Response) SetSuccess(v bool)`

SetSuccess sets Success field to given value.


### GetData

`func (o *V1AnimeGet200Response) GetData() []V1AnimeGet200ResponseDataInner`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *V1AnimeGet200Response) GetDataOk() (*[]V1AnimeGet200ResponseDataInner, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *V1AnimeGet200Response) SetData(v []V1AnimeGet200ResponseDataInner)`

SetData sets Data field to given value.


### GetPagination

`func (o *V1AnimeGet200Response) GetPagination() V1AnimeGet200ResponsePagination`

GetPagination returns the Pagination field if non-nil, zero value otherwise.

### GetPaginationOk

`func (o *V1AnimeGet200Response) GetPaginationOk() (*V1AnimeGet200ResponsePagination, bool)`

GetPaginationOk returns a tuple with the Pagination field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPagination

`func (o *V1AnimeGet200Response) SetPagination(v V1AnimeGet200ResponsePagination)`

SetPagination sets Pagination field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


