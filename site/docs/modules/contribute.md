# Contribute modules

## AddToAny
    * addtoany
    * composer require 'drupal/addtoany:^1.14'
        Share buttons by AddToAny, including the AddToAny universal sharing button, Facebook, Twitter, Google+, Pinterest, and over 100 more on the AddToAny platform.
        Version: 7.x-4.15

## Administration menu
    * admin_menu
    * Is broken for drupal 8. - composer require 'drupal/admin_menu:3.x-dev@dev'
        PProvides a dropdown menu to most administrative tasks and other common destinations (to users with the proper permissions).

## Administration menu Toolbar style
    * admin_menu_toolbar
    * composer require drupal/admin_toolbar - Includes: Administration menu, Administration menu Toolbar style
        Ulepszony pasek administracyjny.

## Administration views 
    * admin_views
    * In Core - Integrate with core view module
        Replaces all system object management pages in Drupal core with real views.

## AdvAgg Bundler
    * advagg_bundler
    * composer require 'drupal/advagg:^4.1'
        Provides intelligent bundling of CSS and JS files by grouping files that belong together.
        
## AdvAgg Modifier
    * advagg_mod
    * Above advagg_bundler will add this modules
        Allows one to alter the CSS and JS array.
        
## Advanced CSS/JS Aggregation
    * advagg
    * Added by above
        Aggregates multiple CSS/JS files in a way that prevents 404 from happening when accessing a CSS or JS file.


## Better Exposed Filters
    * better_exposed_filters
    * composer require 'drupal/better_exposed_filters:^5.0@beta'
        Allow the use of checkboxes or radio buttons for exposed Views filters


## Block
    * block 
    * In drupal 8, seperated in Block and Custom Block modules
    * Inside core
        Controls the visual building blocks a page is constructed with. Blocks are boxes of content rendered into an area, or region, of a web page.
        

## Block Class 
    * block_class
    * composer require 'drupal/block_class:^1.3'
        Allows assigning CSS classes to blocks.

## Block languages 
    * i18n_block
    * In core. Include by internationalization
        Enables language selector for blocks and optional block translation.


## Block reference 
    * blockreference
    * Not available
    * May be alternative - https://ftp.drupal.org/files/projects/block_formatter-8.x-1.0.tar.gz
        Defines a field type for referencing a block from a node.

## Browscap 
    * browscap - Not available for Drupal 9
    * composer require 'drupal/browscap:^3.0@alpha'
        Provides a replacement for PHPs get_browser() function.

## Chaos tools
    * ctools
    * In code - without Page Manager and Form Wizard.
        A library of helpful tools by Merlin of Chaos.

## CKEditor 
    * ckeditor
    * In core - Use Text Editor
        Enables CKEditor (WYSIWYG HTML editor) for use instead of plain text fields.

## CKEditor Link
    * ckeditor_link
    * Not available
        Easily create links to Drupal internal paths through CKEditor.

## Colors 
    * colors
    * composer require 'drupal/colors:^1.0@beta'
        API for coloring selectors.

## Computed Field
    * computed_field
    * composer require 'drupal/computed_field:^2.0'
        Defines a field type that allows values to be "computed" via PHP code.

## Conditional Fields
    * conditional_fields
    * composer require 'drupal/conditional_fields:^1.0@alpha'
        Define dependencies between fields based on their states and values.

## Content Menu
    * content_menu
    * Not available
        Content centric menu management interface for editors.

## Content translation
    * translation
    * In core
        Allows content to be translated into different languages.

## Context 
    * context
    * composer require 'drupal/context:4.x-dev@dev'
        Provide modules with a cache that lasts for a single page request.

## Context layouts
    * context_layouts - Not available for Drupal 9
    * composer require 'drupal/context_layout'
        Allow theme layer to provide multiple region layouts and integrate with context.

## Contextual links
    * contextual
    * In core
        Provides contextual links to perform actions related to elements on a page.

## Corresponding Entity References
    * cer - Not available for Drupal 9
    * composer require 'drupal/cer:^4.0@alpha'
        Syncs the Entity reference between two node types which have an entityreference to each other.

## CORS
    * cors - Not available for Drupal 9
    * composer require 'drupal/cors:^1.0'
        Allows Cross-origin resource sharing.

## Custom breadcrumbs API
    * custom_breadcrumbsapi
    * composer require 'drupal/custom_breadcrumbs'
        Provides a simple API to set breadcrumbs on module pages not served by other custom breadcrumbs submodules.

## Custom breadcrumbs for paths 
    * custom_breadcrumbs_paths
    * Included by above
        Provides custom breadcrumbs for specific paths.

## Custom breadcrumbs for views
    * custom_breadcrumbs_views
    * Included by above
        Provides custom breadcrumbs for views pages.

## Custom breadcrumbs identifiers
    * custom_breadcrumbs_identifiers
    * Included by above
        Provides special identifiers for custom breadcrumbs.

## Custom content panes
    * ctools_custom_content
    * Not availablle (Not sure)
        Create custom, exportable, reusable content panes for applications like Panels.

## Database logging
    * dblog
    * In Core
        Logs and records system events to the database.

## Date 
    * date
    + In core
        Makes date/time fields available.

## Date API
    * date_api
    * In core
        Date API, którego mogą użyć inne moduły.

## Date Popup 
    * date_popup
    * In core
        Udostępnia wyskakujący kalendarz jquery i kontrolki do wprowadzania dat i godzin.

## Date Repeat API
    * date_repeat
    * In core
        Date Repeat API wylicza powtarzające się daty i godziny według zasad iCal.

## Date Repeat Field 
    * date_repeat_field
    * In core
        Creates the option of Repeating date fields and manages Date fields that use the Date Repeat API.

## Date Views 
    * date_views
    * In core
        Integracja z modułem Views dla pól przechowujących daty i funkcji terminów.

## Draggableviews 
    * draggableviews
    * composer require 'drupal/draggableviews:^1.2'
        Dodaje do widoków możliwość sortowania za pomocą metody przeciągnij i upuść

## Editable Fields 
    * editablefields
    * Not available
        Allows you to make some fields editable from the display.

## Elysia Cron
    * elysia_cron
    * Not available
        Extended cron support with crontab-like scheduling and other features.

## Email 
    * email
    * In core
        Defines an email field type

## Entity API 
    * entity
    * In core
        Enables modules to work with any entity type and to provide entities.

## Entity Reference 
    * entityreference
    * In core
        Provides a field that can reference other entities

## Entity tokens 
    * entity_token
    * In core
        Provides token replacements for all properties that have no tokens and are known to the entity API.

## Features 
    * features - In core
    * composer require 'drupal/features:^3.11'
        Provides feature management for Drupal.

## Field 
    * field
    * In core
        Field API to add fields to entities like nodes and users.

## Field collection 
    * field_collection - Not available for drupal 9
    *  composer require 'drupal/field_collection:^1.0@alpha'
        Provides a field collection field, to which any number of fields can be attached.

## Field default token 
    * field_default_token - - Not available for drupal 9
    * composer require 'drupal/field_default_token:1.x-dev@dev'
        Enables to use tokens as field default values.

## Field Group 
    * field_group
    * composer require 'drupal/field_group:^3.1'
        Provides the ability to group your fields on both form and display.

## Field Hidden 
    * field_hidden
    * In core
        Defines hidden field types.

## Field Permissions 
    * field_permissions
    * composer require 'drupal/field_permissions:^1.1'
        Set field-level permissions to create, update or view fields.

## Field SQL storage 
    * field_sql_storage
    * In core
        Stores field data in an SQL database.

## Field translation 
    * i18n_field
    * Not available (Not sure)
        Translate field properties

## Field UI 
    * field_ui
    * In core
        User interface for the Field API.

## Field Validation 
    * field_validation
    * composer require 'drupal/field_validation:^1.0@beta'
        Add validation rules to fields.

## Field validation extras 
    * field_validation_extras
    * Include by field_validation above
        Extra validators for Field validation 7.x-2.x.

## Field Validation UI 
    * field_validation_ui
    * Include by field_validation above
        UI for Field Validation.

## File (Field) Paths
    * filefield_paths
    * composer require 'drupal/filefield_paths:^1.0@beta'
        Adds improved Token based file sorting and renaming functionalities.

## File 
    * file
    * Included by filefield_paths above
        Defines a file field type.

## Filter 
    * filter
    * In core
        Filters content in preparation for display.

## FullCalendar 
    * fullcalendar - User deprecated function error in drupal 9
    * composer require 'drupal/fullcalendar:2.x-dev@dev'
        Provides a views style plugin for FullCalendar

## Global Redirect 
    * globalredirect
    * Only link to file download found - globalredirect-8.x-1.x-dev.tar.gz
        Searches for an alias of the current URL and 301 redirects if found. Stops duplicate content arising when path module is enabled.

## GMap 
    * gmap
    * Not available - Alternative https://www.drupal.org/project/simple_gmap
        Views plugins to show Google Maps from entities.

## GMap Location
    * gmap_location
    * Not available
        Display location.module information on Google Maps

## GMap Macro Builder 
    * gmap_macro_builder
    * Not available
        UI for building GMap macros.

## Help 
    * help
    * In core
        Manages the display of online help.

## Image 
    * image
    * In core
        Provides image manipulation tools.

## Image Allow Insecure Derivatives
    * image_allow_insecure_derivatives
    * Not available
        Provides a configuration option to toggle whether or not Drupal bypasses the token check when generating image derivatives. Warning: Only use this module if you know what you're doing.

## ImageField Tokens 
    * imagefield_tokens
    * composer require 'drupal/imagefield_tokens:^2.22'
        Adds additional settings to the Image field alt/title attributes.

## IMCE 
    * imce
    * composer require 'drupal/imce:^2.3'
        Przeglądarka i narzędzie przesyłania obrazków/plików obsługujące limity użytkownika i katalogi osobiste.

## IMCE for File Field 
    * imce_filefield
    * Not available
        Allows users to select files from IMCE File Browser for file fields.

## Inline Form Errors 
    * ife
    * In core
        Put form error messages inline with the form elements

## Internationalization 
    * i18n
    * In core
        Extends Drupal support for multilingual features.

## jQuery Update 
    * jquery_update
    * In core
        Update jQuery and jQuery UI to a more recent version.

## Libraries 
    * libraries
    * composer require 'drupal/libraries:^3.0@beta'
        Allows version-dependent and shared usage of external libraries.

## Link 
    * link
    * In core
        Definiuje proste pole typu odnośnik

## List 
    * list
    * In core
        Defines list field types. Use with Options to create selection lists.

## Locale 
    * locale
    * In core
        Adds language handling functionality and enables the translation of the user interface to languages other than English.

## Location 
    * location
    * Not available - https://www.drupal.org/project/geolocation
        The location module allows you to associate a geographic location with content and users. Users can do proximity searches by postal code. This is useful for organizing communities that have a geographic presence.

## Login Destination 
    * login_destination
    * composer require 'drupal/login_destination:^1.0@beta'
        Customize the destination that the user is redirected to after login.

## LoginToboggan 
    * logintoboggan - Not availaable for Drupal 9
    * composer require 'drupal/logintoboggan:1.x-dev@dev'
        Improves Drupal's login system.

## Mail System 
    * mailsystem
    * composer require 'drupal/mailsystem:^4.3'
        Provides a user interface for per-module and site-wide mail_system selection.

## Menu 
    * menu
    * In core
        Allows administrators to customize the site navigation menu.

## Menu Block 
    * menu_block
    * composer require 'drupal/menu_block:^1.6'
        Provides configurable blocks of menu items.

## Menu Firstchild 
    * menu_firstchild
    * composer require 'drupal/menu_firstchild:^1.0@RC'
        Allows to create parent menu items without path that link to their first viewable children.

## Menu target 
    * menu_target - Not available for Drupal 9
    * composer require 'drupal/menu_target:1.x-dev@dev'
        Allows administrators to choose wether or not to open menu items in a new window.

## Menu Trail By Path 
    * menu_trail_by_path
    * composer require 'drupal/menu_trail_by_path:^1.3'
        Expand menus and set active-trail according to the current path.

## Menu translation 
    * i18n_menu
    * In core
        OSupports translatable custom menu items.

## Metatag 
    * metatag
    * composer require 'drupal/metatag:^1.15'
        Adds support and an API to implement meta tags.

## Metatag: Open Graph 
    * metatag_opengraph
    * Include by metatag above
        Provides support for open graph meta tags.

## Metatag: Views 
    * metatag_views
    * Include by metatag above
        Provides Metatag integration within the Views interface.

## Mime Mail 
    * mimemail
    * composer require 'drupal/mimemail:^1.0@alpha'
        Send MIME-encoded emails with embedded images and attachments.

## Module filter 
    * module_filter
    * In core - composer require 'drupal/module_filter:^3.1'
        Filter the modules list.

## Multilingual content 
    * i18n_node
    * In core. Included by Internationalization
        Extended node options for multilingual content

## Multilingual select 
    * i18n_select
    * In core. Include by internationalization
        API module for multilingual content selection

## Node 
    * node
    * In core
        Allows content to be submitted to the site and displayed on pages.

## Node clone 
    * clone
    * composer require 'drupal/node_clone:1.x-dev@dev'
        Allows users to clone (copy then edit) an existing node.

## Node locations 
    * location_node
    * Not available
        Associate locations with nodes.

## Number 
    * number
    * In core
        Defines numeric field types.

## Options 
    * options
    * In core
        Defines selection, check box and radio button widgets for text and numeric fields.

## Path 
    * path
    * In core
        Allows users to rename URLs.

## Path translation 
    * i18n_path
    * In core. Included on Internationalization
        Define translations for generic paths

## Pathauto 
    * pathauto
    * composer require 'drupal/pathauto:^1.8'
        Dostarcza modułom mechanizm służący do automatycznego generowania aliasów dla treści, którymi zarządzają.

## PHP filter 
    * php
    * In core
        Allows embedded PHP code/snippets to be evaluated.

## RDF 
    * rdf
    * In core
        Enriches your content with metadata to let other applications (e.g. search engines, aggregators) better understand its relationships and attributes.

## Redirect 
    * redirect
    * composer require 'drupal/redirect:^1.6'
        Allows users to redirect from old URLs to new URLs.

## Redis 
    * redis
    * composer require 'drupal/redis:^1.5'
        Provide a module placeholder, for using as dependency for module that needs Redis.

## Scheduler 
    * scheduler
    * composer require 'drupal/scheduler:^1.3'
        This module allows nodes to be published and unpublished on specified dates and time.

## Semantic Fields
    * semantic_fields
    * Not available
        Provides semantic HTML output settings for each field type.

## Semantic Views
    * semanticviews
    * composer require 'drupal/semanticviews:^2.3'
        Views 3 plugins for UI management of output markup

## String translation 
    * i18n_string
    * In core. Included on internationalization
        Provides support for translation of user defined strings.

## Submit Again
    * submitagain
    * Not available
        Adds an extra button to selected node types *Submit and make another

## System 
    * system
    * In core
        Handles general site configuration for administrators.

## Taxonomy 
    * taxonomy
    * In core
        Enables the categorization of content.

## Taxonomy translation 
    * i18n_taxonomy
    * In core. Included on Internationalization
        Enables multilingual taxonomy.

## Text 
    * text
    * In core
        Defines simple text field types.

## Token 
    * token
    * composer require 'drupal/token:^1.9'
        Provides a user interface for the Token API and some missing core tokens.

## Translation redirect 
    * i18n_redirect
    * In core. Included on Internationalization
        Redirect to translated page when available. SEO for multilingual sites.

## Translation sets 
    * i18n_translation
    * In core. Included on Internationalization
        Simple translation sets API for generic objects

## Transliteration 
    * transliteration
    * In core - No direct support for transliterating path aliases or file names.
        Converts non-latin text to US-ASCII and sanitizes file names.

## User 
    * user
    * In core
        Manages the user registration and login system.

## Variable 
    * variable
    * In core
        Variable Information and basic variable API

## Variable admin 
    * variable_admin
    * In core - Included by Variable
        Variable Administration UI

## Variable realm 
    variable_realm
    * In core - Included by Variable
        API to use variable realms from different modules

## Variable store 
    * variable_store
    * In core - Included by Variable
        Database storage for variable realms. This is an API module.

## Variable translation 
    * i18n_variable
    * In core - Included by Internationalization
        Multilingual variables that switch language depending on page language.

## Video Embed Field 
    * video_embed_field
    * composer require 'drupal/video_embed_field:^2.4'
        Expose a field type for embedding videos from youtube or vimeo.

## Views 
    * views
    * In core
        Create customized lists and queries from your database.

## Views Bulk Operations 
    * views_bulk_operations
    * In core + composer require 'drupal/views_bulk_operations:^3.10'
        Provides a way of selecting multiple rows and applying operations to them.

## Views JSON 
    * views_json
    * In core - The basic functionality is in core, but some advanced features (such as outputting a Views attachment as JSON) are not.
    * Use Views Datasource
        Views style plugin to render node content as JSON.

## Views PHP 
    * views_php - Not vavailable for Drupal 9
    * composer require 'drupal/views_php:1.x-dev@dev'
        Allows the usage of PHP to construct a view.

## Views UI 
    * views_ui
    * In core. Included by Views
        Administrative interface to views. Without this module, you cannot create or edit your views.