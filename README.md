## Drupal Lean starter set

Upon installation, a fresh adaptive theme sub-theme "drupallean" will be enabled together with the following modules:

````
$ drush pm-list | grep Enabled
 Administration    Administration menu (admin_menu)              Module  Enabled        7.x-3.0-rc4   
 Administration    Administration menu Toolbar style             Module  Enabled        7.x-3.0-rc4   
 Administration    Administration views (admin_views)            Module  Enabled        7.x-1.3       
 Administration    Module filter (module_filter)                 Module  Enabled        7.x-2.0-alpha 
 Chaos tool suite  Chaos tools (ctools)                          Module  Enabled        7.x-1.4       
 Chaos tool suite  Page manager (page_manager)                   Module  Enabled        7.x-1.4       
 Chaos tool suite  Views content panes (views_content)           Module  Enabled        7.x-1.4       
 Core              Block (block)                                 Module  Enabled        7.31          
 Core              Color (color)                                 Module  Enabled        7.31          
 Core              Comment (comment)                             Module  Enabled        7.31          
 Core              Contextual links (contextual)                 Module  Enabled        7.31          
 Core              Database logging (dblog)                      Module  Enabled        7.31          
 Core              Field (field)                                 Module  Enabled        7.31          
 Core              Field SQL storage (field_sql_storage)         Module  Enabled        7.31          
 Core              Field UI (field_ui)                           Module  Enabled        7.31          
 Core              File (file)                                   Module  Enabled        7.31          
 Core              Filter (filter)                               Module  Enabled        7.31          
 Core              Help (help)                                   Module  Enabled        7.31          
 Core              Image (image)                                 Module  Enabled        7.31          
 Core              List (list)                                   Module  Enabled        7.31          
 Core              Locale (locale)                               Module  Enabled        7.31          
 Core              Menu (menu)                                   Module  Enabled        7.31          
 Core              Node (node)                                   Module  Enabled        7.31          
 Core              Number (number)                               Module  Enabled        7.31          
 Core              Options (options)                             Module  Enabled        7.31          
 Core              Path (path)                                   Module  Enabled        7.31          
 Core              RDF (rdf)                                     Module  Enabled        7.31          
 Core              Search (search)                               Module  Enabled        7.31          
 Core              Shortcut (shortcut)                           Module  Enabled        7.31          
 Core              System (system)                               Module  Enabled        7.31          
 Core              Taxonomy (taxonomy)                           Module  Enabled        7.31          
 Core              Text (text)                                   Module  Enabled        7.31          
 Core              Update manager (update)                       Module  Enabled        7.31          
 Core              User (user)                                   Module  Enabled        7.31          
 Date/Time         Calendar (calendar)                           Module  Enabled        7.x-3.4       
 Date/Time         Date (date)                                   Module  Enabled        7.x-2.8       
 Date/Time         Date All Day (date_all_day)                   Module  Enabled        7.x-2.8       
 Date/Time         Date API (date_api)                           Module  Enabled        7.x-2.8       
 Date/Time         Date Popup (date_popup)                       Module  Enabled        7.x-2.8       
 Date/Time         Date Views (date_views)                       Module  Enabled        7.x-2.8       
 Development       Delete content and users (delete_all)         Module  Enabled        7.x-1.1       
 Development       Devel (devel)                                 Module  Enabled        7.x-1.5       
 Development       Profiler Builder (profiler_builder)           Module  Enabled        7.x-1.1       
 Entityforms       Entityforms (entityform)                      Module  Enabled        7.x-2.0-beta4 
 Features          Features (features)                           Module  Enabled        7.x-2.2       
 Features extra    FE Block (fe_block)                           Module  Enabled        7.x-1.0-beta1 
 Features extra    FE Nodequeue (fe_nodequeue)                   Module  Enabled        7.x-1.0-beta1 
 Fields            Email (email)                                 Module  Enabled        7.x-1.3       
 Fields            Entity Reference (entityreference)            Module  Enabled        7.x-1.1       
 Fields            File Field Sources (filefield_sources)        Module  Enabled        7.x-1.9       
 Fields            Link (link)                                   Module  Enabled        7.x-1.2       
 Nodequeue         Nodequeue (nodequeue)                         Module  Enabled        7.x-2.0-beta1 
 Other             AddToAny (addtoany)                           Module  Enabled        7.x-4.5       
 Other             Advanced help (advanced_help)                 Module  Enabled        7.x-1.1       
 Other             Automatic Entity Labels (auto_entitylabel)    Module  Enabled        7.x-1.2       
 Other             Diff (diff)                                   Module  Enabled        7.x-3.2       
 Other             Entity API (entity)                           Module  Enabled        7.x-1.5       
 Other             Entity tokens (entity_token)                  Module  Enabled        7.x-1.5       
 Other             Insert (insert)                               Module  Enabled        7.x-1.3       
 Other             Libraries (libraries)                         Module  Enabled        7.x-2.2       
 Other             Masquerade (masquerade)                       Module  Enabled        7.x-1.0-rc7   
 Other             Pathauto (pathauto)                           Module  Enabled        7.x-1.2       
 Other             Redirect (redirect)                           Module  Enabled        7.x-1.0-rc1   
 Other             Simple Google Maps (simple_gmap)              Module  Enabled        7.x-1.2       
 Other             Strongarm (strongarm)                         Module  Enabled        7.x-2.0       
 Other             Token (token)                                 Module  Enabled        7.x-1.5       
 Panels            Mini panels (panels_mini)                     Module  Enabled        7.x-3.4       
 Panels            Panel pane suggestions (pps)                  Module  Enabled        7.x-1.0       
 Panels            Panels (panels)                               Module  Enabled        7.x-3.4       
 Path management   Global Redirect (globalredirect)              Module  Enabled        7.x-1.5       
 Printer, email    Printer-friendly pages (print)                Module  Enabled        7.x-2.0       
 Printer, email    Printer-friendly pages UI (print_ui)          Module  Enabled        7.x-2.0       
 Printer, email    Send by email (print_mail)                    Module  Enabled        7.x-2.0       
 User interface    CKEditor (ckeditor)                           Module  Enabled        7.x-1.15      
 User interface    Superfish (superfish)                         Module  Enabled        7.x-1.9       
 Views             Similar By Terms (similarterms)               Module  Enabled        7.x-2.3       
 Views             Views (views)                                 Module  Enabled        7.x-3.8       
 Views             Views Bulk Operations                         Module  Enabled        7.x-3.2       
 Views             Views Slideshow (views_slideshow)             Module  Enabled        7.x-3.1       
 Views             Views Slideshow: Cycle                        Module  Enabled        7.x-3.1       
 Views             Views UI (views_ui)                           Module  Enabled        7.x-3.8       
 Core              Seven (seven)                                 Theme   Enabled        7.31          
 Other             DrupalLean (drupallean)                       Theme   Enabled        7.x-3.2       
````
