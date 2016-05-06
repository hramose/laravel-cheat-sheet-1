[@extends('layout.name')](https://laravel.com/docs/master/blade#extending-a-layout)

**en** Called from a child view to extend master layout.

**ru** Расширяет родительское представление, вызывается из дочернего.
 
[@yield('name')](https://laravel.com/docs/master/blade#defining-a-layout)

**en** Display the contents of a given @section.

**ru** Отображает содержимое данной секции @section.

[@section('name')](https://laravel.com/docs/master/blade#defining-a-layout)

**en** Defines a section of content.

**ru** Создает сожержимое секции. 

[@show](https://laravel.com/docs/master/blade#defining-a-layout)

**en** NA

**ru** NA

[@stop](https://laravel.com/docs/5.0/templates#blade-templating)

**en** NA

**ru** NA

[@parent](https://laravel.com/docs/master/blade#extending-a-layout)

**en** NA

**ru** NA

[@append](append)

**en** NA

**ru** NA

[@overwrite](overwrite)

**en** NA

**ru** NA

[@include('view.name')](https://laravel.com/docs/master/blade#control-structures)

**en** Allows you to include a view from within an existing view. All variables that are available to the parent view will be made available to the included view.

**ru** Позволяет вставлять указанное представление в текущее представление. Все переменные, доступные текущему представлению, будут доступны дочернему.

[@include('view.name', array('key' => 'value'))](https://laravel.com/docs/master/blade#control-structures)

**en** Passes an array of extra data to the included view.

**ru** Передает массив дополнительных данных во вставляемое представление.

[@lang('messages.name')](lang)

**en** NA

**ru** NA

[@choice](choice)

**en** NA

**ru** NA

[@if](https://laravel.com/docs/5.2/blade#control-structures)

**en** NA

**ru** NA

[@else](https://laravel.com/docs/5.2/blade#control-structures)

**en** NA

**ru** NA

[@elseif](https://laravel.com/docs/5.2/blade#control-structures)

**en** NA

**ru** NA

[@endif](https://laravel.com/docs/5.2/blade#control-structures)

**en** NA

**ru** NA

[@unless](unless)

**en** NA

**ru** NA

[@endunless](endunless)

**en** NA

**ru** NA

[@for](for)

**en** NA

**ru** NA

[@endfor](endfor)

**en** NA

**ru** NA

[@foreach](foreach)

**en** NA

**ru** NA

[@endforeach](endforeach)

**en** NA

**ru** NA

[@while](while)

**en** NA

**ru** NA

[@endwhile](endwhile)

**en** NA

**ru** NA

[@forelse($users as $user)](forelse)

**en** NA

**ru** NA

[@empty](empty)

**en** NA

**ru** NA

[@endforelse](endforelse)

**en** NA

**ru** NA

[{{ $escapedVariable }}](escaped)

**en** NA

**ru** NA

[{!! $unescapedVariable !!}](unescaped)

**en** NA

**ru** NA

[{{-- Blade Comment --}}](comment)

**en** NA

**ru** NA

[{{ $name or 'Default' }}](or)

**en** NA

**ru** NA

[@{{ This will not be processed by Blade }}](notprocessed)

**en** NA

**ru** NA

[@stack(name)](stack)

**en** NA

**ru** NA

[@push(name)](push)

**en** NA

**ru** NA
