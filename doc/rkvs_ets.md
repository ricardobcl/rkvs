

# Module rkvs_ets #
* [Description](#description)
* [Function Index](#index)
* [Function Details](#functions)


ETS backend
Note: value encoding is ignored since everything is encoded as a term.
__Behaviours:__ [`rkvs_storage_backend`](rkvs_storage_backend.md).
<a name="index"></a>

## Function Index ##


<table width="100%" border="1" cellspacing="0" cellpadding="2" summary="function index"><tr><td valign="top"><a href="#clear-2">clear/2</a></td><td></td></tr><tr><td valign="top"><a href="#clear_range-4">clear_range/4</a></td><td></td></tr><tr><td valign="top"><a href="#close-1">close/1</a></td><td></td></tr><tr><td valign="top"><a href="#contains-2">contains/2</a></td><td></td></tr><tr><td valign="top"><a href="#destroy-1">destroy/1</a></td><td></td></tr><tr><td valign="top"><a href="#fold-4">fold/4</a></td><td></td></tr><tr><td valign="top"><a href="#fold_keys-4">fold_keys/4</a></td><td></td></tr><tr><td valign="top"><a href="#get-2">get/2</a></td><td></td></tr><tr><td valign="top"><a href="#is_empty-1">is_empty/1</a></td><td>Returns true if this backend contains any values; otherwise returns false.</td></tr><tr><td valign="top"><a href="#open-2">open/2</a></td><td></td></tr><tr><td valign="top"><a href="#put-3">put/3</a></td><td></td></tr><tr><td valign="top"><a href="#scan-4">scan/4</a></td><td></td></tr><tr><td valign="top"><a href="#write_batch-2">write_batch/2</a></td><td></td></tr></table>


<a name="functions"></a>

## Function Details ##

<a name="clear-2"></a>

### clear/2 ###

`clear(Engine, Key) -> any()`


<a name="clear_range-4"></a>

### clear_range/4 ###

`clear_range(Engine, Start, End, Max) -> any()`


<a name="close-1"></a>

### close/1 ###

`close(Engine) -> any()`


<a name="contains-2"></a>

### contains/2 ###

`contains(Engine, Key) -> any()`


<a name="destroy-1"></a>

### destroy/1 ###

`destroy(Engine) -> any()`


<a name="fold-4"></a>

### fold/4 ###

`fold(Engine, Fun, Acc0, Opts) -> any()`


<a name="fold_keys-4"></a>

### fold_keys/4 ###

`fold_keys(Engine, Fun, Acc0, Opts) -> any()`


<a name="get-2"></a>

### get/2 ###

`get(Engine, Key) -> any()`


<a name="is_empty-1"></a>

### is_empty/1 ###


<pre><code>
is_empty(Engine::<a href="#type-engine">engine()</a>) -&gt; boolean() | {error, term()}
</code></pre>
<br />

Returns true if this backend contains any values; otherwise returns false.
<a name="open-2"></a>

### open/2 ###

`open(Name, Options) -> any()`


<a name="put-3"></a>

### put/3 ###

`put(Engine, Key, Value) -> any()`


<a name="scan-4"></a>

### scan/4 ###

`scan(Engine, Start, End, Max) -> any()`


<a name="write_batch-2"></a>

### write_batch/2 ###

`write_batch(Engine, Ops) -> any()`


