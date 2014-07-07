<h1>Using capistrano to deploy this test project</h1>
<br>
Rails version: v3.2.17<br>
Ruby version: v1.9.3p547<br>
Server: Ubuntu Server 14.04 LTS (PV)<br>
<br>
Using these gems:<br>
&nbsp;'capistrano', '~>3.2.1'<br>
&nbsp;'capistrano-rails'<br>
&nbsp;'capistrano-bundler'<br>
&nbsp;'capistrano-rvm'<br>
&nbsp;'sepastian-capistrano3-unicorn'<br>
<br>
capistrano config:<br>
&nbsp;Capfile
&nbsp;production.rb, path => config/deploy/production.rb<br>
&nbsp;deploy.rb, path => config/deploy.rb<br>
<br>
unicorn config:<br>
&nbsp;unicorn.rb, path => config/unicorn.rb<br>
