(l-mod-onnx-helper)=

# onnx.helper

```{eval-rst}
.. currentmodule:: onnx.helper
```

```{eval-rst}
.. autosummary::

    find_min_ir_version_for
    get_all_tensor_dtypes
    get_attribute_value
    get_node_attr_value
    set_metadata_props
    set_model_props
    float32_to_bfloat16
    float32_to_float8e4m3
    float32_to_float8e5m2
    make_attribute
    make_attribute_ref
    make_empty_tensor_value_info
    make_function
    make_graph
    make_map
    make_map_type_proto
    make_model
    make_node
    make_operatorsetid
    make_opsetid
    make_model_gen_version
    make_optional
    make_optional_type_proto
    make_sequence
    make_sequence_type_proto
    make_sparse_tensor
    make_sparse_tensor_type_proto
    make_sparse_tensor_value_info
    make_tensor
    make_tensor_sequence_value_info
    make_tensor_type_proto
    make_training_info
    make_tensor_value_info
    make_value_info
    np_dtype_to_tensor_dtype
    printable_attribute
    printable_dim
    printable_graph
    printable_node
    printable_tensor_proto
    printable_type
    printable_value_info
    split_complex_to_pairs
    create_op_set_id_version_map
    strip_doc_string
    pack_float32_to_4bit
    tensor_dtype_to_np_dtype
    tensor_dtype_to_storage_tensor_dtype
    tensor_dtype_to_string
    tensor_dtype_to_field
```

## getter

```{eval-rst}
.. autofunction:: onnx.helper.get_attribute_value
```

```{eval-rst}
.. autofunction:: onnx.helper.get_node_attr_value
```

## setter

```{eval-rst}
.. autofunction:: onnx.helper.set_metadata_props
```

```{eval-rst}
.. autofunction:: onnx.helper.set_model_props
```

## print

```{eval-rst}
.. autofunction:: onnx.helper.printable_attribute
```

```{eval-rst}
.. autofunction:: onnx.helper.printable_dim
```

```{eval-rst}
.. autofunction:: onnx.helper.printable_graph
```

```{eval-rst}
.. autofunction:: onnx.helper.printable_node
```

```{eval-rst}
.. autofunction:: onnx.helper.printable_tensor_proto
```

```{eval-rst}
.. autofunction:: onnx.helper.printable_type
```

```{eval-rst}
.. autofunction:: onnx.helper.printable_value_info
```

## tools

```{eval-rst}
.. autofunction:: onnx.helper.find_min_ir_version_for
```

```{eval-rst}
.. autofunction:: onnx.helper.split_complex_to_pairs
```

```{eval-rst}
.. autofunction:: onnx.helper.create_op_set_id_version_map
```

```{eval-rst}
.. autofunction:: onnx.helper.strip_doc_string
```

```{eval-rst}
.. autofunction:: onnx.helper.pack_float32_to_4bit
```

(l-onnx-make-function)=

## make function

All functions used to create an ONNX graph.

```{eval-rst}
.. autofunction:: onnx.helper.make_attribute
```

```{eval-rst}
.. autofunction:: onnx.helper.make_attribute_ref
```

```{eval-rst}
.. autofunction:: onnx.helper.make_empty_tensor_value_info
```

```{eval-rst}
.. autofunction:: onnx.helper.make_function
```

```{eval-rst}
.. autofunction:: onnx.helper.make_graph
```

```{eval-rst}
.. autofunction:: onnx.helper.make_map
```

```{eval-rst}
.. autofunction:: onnx.helper.make_map_type_proto
```

```{eval-rst}
.. autofunction:: onnx.helper.make_model
```

```{eval-rst}
.. autofunction:: onnx.helper.make_node
```

```{eval-rst}
.. autofunction:: onnx.helper.make_operatorsetid
```

```{eval-rst}
.. autofunction:: onnx.helper.make_opsetid
```

```{eval-rst}
.. autofunction:: onnx.helper.make_model_gen_version
```

```{eval-rst}
.. autofunction:: onnx.helper.make_optional
```

```{eval-rst}
.. autofunction:: onnx.helper.make_optional_type_proto
```

```{eval-rst}
.. autofunction:: onnx.helper.make_sequence
```

```{eval-rst}
.. autofunction:: onnx.helper.make_sequence_type_proto
```

```{eval-rst}
.. autofunction:: onnx.helper.make_sparse_tensor
```

```{eval-rst}
.. autofunction:: onnx.helper.make_sparse_tensor_type_proto
```

```{eval-rst}
.. autofunction:: onnx.helper.make_sparse_tensor_value_info
```

```{eval-rst}
.. autofunction:: onnx.helper.make_tensor
```

```{eval-rst}
.. autofunction:: onnx.helper.make_tensor_sequence_value_info
```

```{eval-rst}
.. autofunction:: onnx.helper.make_tensor_type_proto
```

```{eval-rst}
.. autofunction:: onnx.helper.make_training_info
```

```{eval-rst}
.. autofunction:: onnx.helper.make_tensor_value_info
```

```{eval-rst}
.. autofunction:: onnx.helper.make_value_info
```

## type mappings

```{eval-rst}
.. autofunction:: onnx.helper.get_all_tensor_dtypes
```

```{eval-rst}
.. autofunction:: onnx.helper.np_dtype_to_tensor_dtype
```

```{eval-rst}
.. autofunction:: onnx.helper.tensor_dtype_to_field
```

```{eval-rst}
.. autofunction:: onnx.helper.tensor_dtype_to_np_dtype
```

```{eval-rst}
.. autofunction:: onnx.helper.tensor_dtype_to_storage_tensor_dtype
```

```{eval-rst}
.. autofunction:: onnx.helper.tensor_dtype_to_string
```

## cast

```{eval-rst}
.. autofunction:: onnx.helper.float32_to_bfloat16
```

```{eval-rst}
.. autofunction:: onnx.helper.float32_to_float8e4m3
```

```{eval-rst}
.. autofunction:: onnx.helper.float32_to_float8e5m2
```
