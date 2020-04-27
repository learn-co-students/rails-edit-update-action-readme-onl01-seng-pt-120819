<%= form_tag articles_path do %>
    <label>Article Title:</label><br>
    <%= text_field_tag :'article[title]' %><br>
   
    <label>Content:</label><br>
    <%= text_field_tag :'article[description]' %><br>
   
    <%= submit_tag "Submit Article" %>
<% end %>