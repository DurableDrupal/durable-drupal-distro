## Drupal Lean starter set

Upon installation, a fresh adaptive theme sub-theme "drupallean" will be enabled together with the following modules:

````
$ drush pm-list | grep Enabled
tput: unknown terminal "xterm-256color"
 Administrat  Administration menu (admin_menu)   Module  Enabled        7.x-3.0 
 Administrat  Administration menu Toolbar style  Module  Enabled        7.x-3.0 
 Administrat  Module filter (module_filter)      Module  Enabled        7.x-2.0 
 Chaos tool   Chaos tools (ctools)               Module  Enabled        7.x-1.4 
 Chaos tool   Page manager (page_manager)        Module  Enabled        7.x-1.4 
 Chaos tool   Views content panes                Module  Enabled        7.x-1.4 
 Core         Block (block)                      Module  Enabled        7.28    
 Core         Color (color)                      Module  Enabled        7.28    
 Core         Comment (comment)                  Module  Enabled        7.28    
 Core         Contextual links (contextual)      Module  Enabled        7.28    
 Core         Database logging (dblog)           Module  Enabled        7.28    
 Core         Field (field)                      Module  Enabled        7.28    
 Core         Field SQL storage                  Module  Enabled        7.28    
 Core         Field UI (field_ui)                Module  Enabled        7.28    
 Core         File (file)                        Module  Enabled        7.28    
 Core         Filter (filter)                    Module  Enabled        7.28    
 Core         Help (help)                        Module  Enabled        7.28    
 Core         Image (image)                      Module  Enabled        7.28    
 Core         List (list)                        Module  Enabled        7.28    
 Core         Locale (locale)                    Module  Enabled        7.28    
 Core         Menu (menu)                        Module  Enabled        7.28    
 Core         Node (node)                        Module  Enabled        7.28    
 Core         Number (number)                    Module  Enabled        7.28    
 Core         Options (options)                  Module  Enabled        7.28    
 Core         Path (path)                        Module  Enabled        7.28    
 Core         RDF (rdf)                          Module  Enabled        7.28    
 Core         Search (search)                    Module  Enabled        7.28    
 Core         Shortcut (shortcut)                Module  Enabled        7.28    
 Core         System (system)                    Module  Enabled        7.28    
 Core         Taxonomy (taxonomy)                Module  Enabled        7.28    
 Core         Text (text)                        Module  Enabled        7.28    
 Core         Update manager (update)            Module  Enabled        7.28    
 Core         User (user)                        Module  Enabled        7.28    
 Date/Time    Date (date)                        Module  Enabled        7.x-2.7 
 Date/Time    Date All Day (date_all_day)        Module  Enabled        7.x-2.7 
 Date/Time    Date API (date_api)                Module  Enabled        7.x-2.7 
 Date/Time    Date Popup (date_popup)            Module  Enabled        7.x-2.7 
 Date/Time    Date Views (date_views)            Module  Enabled        7.x-2.7 
 Development  Delete content and users           Module  Enabled        7.x-1.1 
 Development  Devel (devel)                      Module  Enabled        7.x-1.5 
 Development  Profiler Builder                   Module  Enabled        7.x-1.0 
 Features     Features (features)                Module  Enabled        7.x-2.0 
 Fields       Email (email)                      Module  Enabled        7.x-1.3 
 Fields       Entity Reference                   Module  Enabled        7.x-1.1 
 Fields       File Field Sources                 Module  Enabled        7.x-1.9 
 Fields       Link (link)                        Module  Enabled        7.x-1.2 
 Nodequeue    Nodequeue (nodequeue)              Module  Enabled        7.x-2.0 
 Other        AddToAny (addtoany)                Module  Enabled        7.x-4.5 
 Other        Advanced help (advanced_help)      Module  Enabled        7.x-1.1 
 Other        Automatic Nodetitles               Module  Enabled        7.x-1.0 
 Other        Diff (diff)                        Module  Enabled        7.x-3.2 
 Other        Entity API (entity)                Module  Enabled        7.x-1.5 
 Other        Entity tokens (entity_token)       Module  Enabled        7.x-1.5 
 Other        Insert (insert)                    Module  Enabled        7.x-1.3 
 Other        Libraries (libraries)              Module  Enabled        7.x-2.2 
 Other        Masquerade (masquerade)            Module  Enabled        7.x-1.0 
 Other        Pathauto (pathauto)                Module  Enabled        7.x-1.2 
 Other        Redirect (redirect)                Module  Enabled        7.x-1.0 
 Other        Simple Google Maps (simple_gmap)   Module  Enabled        7.x-1.2 
 Other        Strongarm (strongarm)              Module  Enabled        7.x-2.0 
 Other        Token (token)                      Module  Enabled        7.x-1.5 
 Panels       Mini panels (panels_mini)          Module  Enabled        7.x-3.4 
 Panels       Panelizer (panelizer)              Module  Enabled        7.x-3.1 
 Panels       Panels (panels)                    Module  Enabled        7.x-3.4 
 Path         Global Redirect (globalredirect)   Module  Enabled        7.x-1.5 
 Printer,     Printer-friendly pages (print)     Module  Enabled        7.x-2.0 
 Printer,     Printer-friendly pages UI          Module  Enabled        7.x-2.0 
 Printer,     Send by email (print_mail)         Module  Enabled        7.x-2.0 
 User         CKEditor (ckeditor)                Module  Enabled        7.x-1.1 
 User         Superfish (superfish)              Module  Enabled        7.x-1.9 
 Views        Similar By Terms (similarterms)    Module  Enabled        7.x-2.3 
 Views        Views (views)                      Module  Enabled        7.x-3.7 
 Views        Views Bulk Operations              Module  Enabled        7.x-3.2 
 Views        Views Slideshow (views_slideshow)  Module  Enabled        7.x-3.1 
 Views        Views Slideshow: Cycle             Module  Enabled        7.x-3.1 
 Views        Views UI (views_ui)                Module  Enabled        7.x-3.7 
 Core         Seven (seven)                      Theme   Enabled        7.28    
 Other        DrupalLean (drupallean)            Theme   Enabled        7.x-3.2
````
