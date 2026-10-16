# V1CommentsPost201Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Success** | **bool** |  | 
**Data** | [**V1CommentsGet200ResponseDataInner**](V1CommentsGet200ResponseDataInner.md) |  | 

## Methods

### NewV1CommentsPost201Response

`func NewV1CommentsPost201Response(success bool, data V1CommentsGet200ResponseDataInner, ) *V1CommentsPost201Response`

NewV1CommentsPost201Response instantiates a new V1CommentsPost201Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1CommentsPost201ResponseWithDefaults

`func NewV1CommentsPost201ResponseWithDefaults() *V1CommentsPost201Response`

NewV1CommentsPost201ResponseWithDefaults instantiates a new V1CommentsPost201Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSuccess

`func (o *V1CommentsPost201Response) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *V1CommentsPost201Response) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *V1CommentsPost201Response) SetSuccess(v bool)`

SetSuccess sets Success field to given value.


### GetData

`func (o *V1CommentsPost201Response) GetData() V1CommentsGet200ResponseDataInner`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *V1CommentsPost201Response) GetDataOk() (*V1CommentsGet200ResponseDataInner, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *V1CommentsPost201Response) SetData(v V1CommentsGet200ResponseDataInner)`

SetData sets Data field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


