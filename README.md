sub_category = $('#sub_category').val();
    console.log('Category:', category);
    console.log('Sub Category:', sub_category);
    setTimeout(function() {
      if (category && sub_category === null) {
        getSubcategoryByCategoryId(category);
      }
    }, 100);
