# Total-Labels-Labels-
Total Labels (Labels)
$.ajax({

  url: "/feeds/posts/default?alt=json-in-script",

  type: "get",

  dataType: "jsonp",

  success: function(data) {

    var totallabels = data.feed.category.length;

    $('.total-labels').html(totallabels);

  }

});
