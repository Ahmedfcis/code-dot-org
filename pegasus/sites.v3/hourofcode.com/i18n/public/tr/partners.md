---

title: <%= hoc_s(:title_partners) %>

---


<% if @country == 'la' %>

# Latin America Partners

<%= view :about_logos, logos:DB[:cdo_partners].where(hourofcode_b:true).and(kind_s:'la') %>

<% end %>

<% if @country == 'ac' %>

# Africa Partners

<%= view :about_logos, logos:DB[:cdo_partners].where(hourofcode_b:true).and(kind_s:'ac') %>

<% end %>

<% if @country == 'au' %>

# Australia Partners

<%= view :about_logos, logos:DB[:cdo_partners].where(hourofcode_b:true).and(kind_s:'au') %>

<% end %>

<% if @country == 'id' %>

# Indonesia Partners

<%= view :about_logos, logos:DB[:cdo_partners].where(hourofcode_b:true).and(kind_s:'id') %>

<% end %>

<% if @country == 'ie' %>

# Ireland Partners

<%= view :about_logos, logos:DB[:cdo_partners].where(hourofcode_b:true).and(kind_s:'ie') %>

<% end %>

<% if @country == 'in' %>

# India Partners

<%= view :about_logos, logos:DB[:cdo_partners].where(hourofcode_b:true).and(kind_s:'in') %>

<% end %>

<% if @country == 'jp' %>

# Japan Partners

<%= view :about_logos, logos:DB[:cdo_partners].where(hourofcode_b:true).and(kind_s:'jp') %>

<% end %>

<% if @country == 'nz' %>

# New Zealand Partners

<%= view :about_logos, logos:DB[:cdo_partners].where(hourofcode_b:true).and(kind_s:'nz') %>

<% end %>

<% if @country == 'uk' %>

# United Kingdom Partners

<%= view :about_logos, logos:DB[:cdo_partners].where(hourofcode_b:true).and(kind_s:'uk') %>

<% end %>

<% if @country == 'ca' %>

# Canada Partners

<%= view :about_logos, logos:DB[:cdo_partners].where(hourofcode_b:true).and(kind_s:'ca') %>

<% end %>

# Büyük Ortaklar ve Kurumsal Destekçiler

<%= view :about_logos, logos:DB[:cdo_partners].where(hourofcode_b:true).and(kind_s:'major') %>

---

# Büyük Promosyon Ortakları

<%= view :about_logos, logos:DB[:cdo_partners].where(hourofcode_b:true).and(kind_s:'promotional') %>

---

# Uluslararası Partnerler

<%= view :about_logos, logos:DB[:cdo_partners].where(hourofcode_b:true).and(kind_s:'international') %>

---

# Eğitici Partnerleri

<%= view :about_logos, logos:DB[:cdo_partners].where(hourofcode_b:true).and(kind_s:'tutorial') %>

---

# Altyapı partnerleri ve araçlar

<%= view :about_logos, logos:DB[:cdo_partners].where(hourofcode_b:true).and(kind_s:'infrastructure') %>

---

# Diğer Ortaklar

<%= view :about_logos, logos:DB[:cdo_partners].where(hourofcode_b:true).and(kind_s:'additional') %>

