{% assign image_files = site.static_files | where: "image", true %}
<ul class="flexbin flexbin-margin">
{% for myimage in image_files %}
      <a href="{{ site.baseurl }}{{ myimage.path }}">
        <img src="{{ site.baseurl }}{{ myimage.path }}" alt="{{ myimage.title }}">
      </a>
{% endfor %}
<ul>