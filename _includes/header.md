<header>
    <div class="top">
        <a href="{{ '/' | relative_url }}" class="logo"></a>
        <div style="display:inline-block; text-align:center; float:right;">
            <h3 style="margin-bottom:0; font-weight:400;">Hosted by:</h3> 
          <img src="{{ 'assets/img/TAU_logo.png' | relative_url }}">
        </div>
    </div>
	
    <nav>
        <ul class="nav navbar-nav">
            {% for menu in site.data.menus %}
            <li>
                <a href="{{ menu.url | relative_url }}">{{menu.title}}</a>
            </li>
            {% endfor %}
        </ul>
    </nav>
</header>
