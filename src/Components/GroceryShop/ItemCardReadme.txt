

Atchollish
<Button
onClick={() => axios.delete("https://grocersss-d8d44-default-rtdb.firebaseio.com/productData/" + props.item.id + ".json")
                                  .then(response => {
                                      handleClickVariant('error');
                                      toggleDelItemModal();
                                  })}
                            color="danger" style={{ marginRight: "10px" }} size="sm">
                            Delete <DeleteIcon />
                        </Button>