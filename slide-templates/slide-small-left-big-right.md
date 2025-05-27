<grid drag="100 10" drop="top" align="left" pad="80px 20px">
 <% title %>
</grid>

<grid drag="30 80" drop="3 15" align="left">

<% left %>

</grid>

<grid drag="60 80" drop="36 15" align="left">

<% right %>

</grid>

<% content %>

<style>
.horizontal_dotted_line{
  border-bottom: 2px dotted gray;
} 
} 
</style>

<grid drag="94 0" drop="3 -5" class="horizontal_dotted_line">
</grid>

<grid drag="94 0" drop="3 -1">
<%? source %>
</grid>
