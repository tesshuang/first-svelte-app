<script>

  document.addEventListener('DOMContentLoaded', function() {
    let elems = document.querySelectorAll('.materialboxed');
    let instances = M.Materialbox.init(elems, options);
    var instance = M.Materialbox.getInstance(elem);
  });
</script>

<div>
  <img src="https://source.unsplash.com/daily" alt="daily Image" data-caption="Daily image from unsplash" width="350" class="materialboxed responsive-img">
</div>