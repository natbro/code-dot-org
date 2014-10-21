---
title: Takk for at du meldte deg på som vert for Kodetimen!
layout: wide
---
<%
  facebook = {:u=>"http://#{request.host}/us"}

  twitter = {:url=>"http://hourofcode.com", :related=>'codeorg', :hashtags=>'', :text=>hoc_s(:twitter_default_text)}
  twitter[:hashtags] = 'HourOfCode' unless hoc_s(:twitter_default_text).include? '#HourOfCode'
%>

# Takk for at du meldte deg på som vert for Kodetimen!

**ALLE** som organiserer en Kodetime får 10 GB Dropbox-lagringsplass eller $10 Skype-kredit som en takk. [Detaljer](/prizes)

<% if @country == 'us' %>

Få hele [skolen din til å delta](/us/prizes) for å gi den en sjanse til å vinne store premier.

<% end %>

## 1. Spre ordet

Fortell vennene dine om #Kodetimen.

<%= view :share_buttons, facebook:facebook, twitter:twitter %>

<% if @country == 'us' %>

## 2. Spør hele skolen din om å tilby en Kodetime

[Send denne eposten](/resources#email) eller [gi denne flyeren til rektoren din](/files/schools-handout.pdf). Når skolen din har meldt seg på, [bli med i konkurransen om $10,000 i datautstyr til din skole](/prizes) og utfordre andre skoler i ditt område til å bli med.

<% else %>

## 2. Spør hele skolen din om å tilby en Kodetime

[Send this email](/resources#email) or give [this handout](/files/schools-handout.pdf) to your principal.

<% end %>

## 3. Make a generous donation

[Donate to our crowdfunding campaign](http://code.org/donate). To teach 100 million children, we need your support. We just launched what could be the [largest education crowdfunding campaign](http://code.org/donate) in history. Every dollar will be matched by major Code.org [donors](http://code.org/about/donors), doubling your impact.

## 4. Ask your employer to get involved

[Send this email](/resources#email) to your manager, or the CEO. Or [give them this handout](/resources/hoc-one-pager.pdf).

## 5. Promote Hour of Code within your community

Recruit a local group — boy scouts club, church, university, veterans group or labor union. Or host an Hour of Code "block party" for your neighborhood.

## 6. Ask a local elected official to support the Hour of Code

[Send this email](/resources#politicians) to your mayor, city council, or school board. Or [give them this handout](/resources/hoc-one-pager.pdf) and invite them to visit your school.

<%= view 'popup_window.js' %>