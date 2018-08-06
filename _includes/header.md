<header>
    <div class="top">
        <a href="{{ '/' | relative_url }}" class="logo"></a>
	<span style="align:right">
		<div style="text-align:right;" >
			<img src="{{ 'assets/img/TAU_logo.png' | relative_url }}">
		</div>
    	</span>
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
