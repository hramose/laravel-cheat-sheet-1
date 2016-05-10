[@extends('layout.name')](https://laravel.com/docs/master/blade#extending-a-layout)

en
> Called from a child view to extend master layout.

ru
> Расширяет родительское представление, вызывается из дочернего.

[@yield('name')](https://laravel.com/docs/master/blade#defining-a-layout)

en
> Display the contents of a given @section.
ru
> Отображает содержимое данной секции @section.

[@section('name')](https://laravel.com/docs/master/blade#defining-a-layout)

en
> Defines a section of content.

ru
> Создает сожержимое секции. 

[@show](https://laravel.com/docs/master/blade#defining-a-layout)

en
> Yields section content and ends section.

ru
> Отображает содержимое секции и завершает ее.

[@stop](https://laravel.com/docs/5.0/templates#blade-templating)

en
> Ends section.

ru
> Закрывает секцию.

[@parent](https://laravel.com/docs/master/blade#extending-a-layout)

en
> Appends (rather than overwriting) content to the a section. The directive will be replaced by the content of the layout when the view is rendered.

ru
> Добавляет содержимое к секции, не перезаписывая его. Сама директива будет замещена содержимым родительского представления.

[@hasSection('title')](https://laravel.com/docs/master/blade#control-structures)

en
> Determines if a given layout section has any content.

ru
> Определяет имеет ли передаваемый вид какое-либо содержимое.

[@append](append)

en
> Concatenates section content to section content of a master layout. Used instead of @stop directive.

ru
> Добавляет содержимое секции к содержимому секции в родительском представлении. Используется вместо @stop.

[@overwrite](overwrite)

en
>Overwrites content of previous section with the same name. Used instead of @stop directive.
>
>
>     @section('name')
>
>         content1
>
>     @stop
>
>     @section('name')
>
>         content2
>
>     @stop
>
>     @yield('name')
>
> Result:
>
>     content2

ru
> Перезаписывает содержимое любой предыдущей секции с таким же именем. Используется вместо @stop.

[@include('view.name')](https://laravel.com/docs/master/blade#control-structures)

en
> Allows you to include a view from within an existing view. All variables that are available to the parent view will be made available to the included view.

ru
> Позволяет вставлять указанное представление в текущее представление. Все переменные, доступные текущему представлению, будут доступны дочернему.

[@include('view.name', array('key' => 'value'))](https://laravel.com/docs/master/blade#control-structures)

en
> Passes an array of extra data to the included view.

ru
> Передает массив дополнительных данных во вставляемое представление.

[@lang('messages.name')](lang)

en
>

ru
>

[@choice](choice)

en
>

ru
>

[@if](https://laravel.com/docs/5.2/blade#control-structures)

en


ru
>

[@else](https://laravel.com/docs/5.2/blade#control-structures)

en
>

ru
>

[@elseif](https://laravel.com/docs/5.2/blade#control-structures)

en
>

ru
>

[@elsecan]()

en
>

ru
>

[@elsecannot]()

en
>

ru
>

[@endif](https://laravel.com/docs/5.2/blade#control-structures)

en
>

ru
>

[@unless](unless)

en
>

ru
>

[@endunless](endunless)

en
>

ru
>

[@for](for)

en
>

ru
>

[@endfor](endfor)

en
>

ru
>

[@foreach](foreach)

en
>

ru
>

[@endforeach](endforeach)

en
>

ru
>

[@while](while)

en
>

ru
>

[@endwhile](endwhile)

en
>

ru
>

[@forelse($users as $user)](forelse)

en
>

ru
>

[@empty](empty)

en
>

ru
>

[@endforelse](endforelse)

en
>

ru
>

[{{ $escapedVariable }}](escaped)

en
>

ru
>

[{!! $unescapedVariable !!}](unescaped)

en
>

ru
>

[{{-- Blade Comment --}}](comment)

en
>

ru
>

[{{ $name or 'Default' }}](or)

en
>

ru
>

[@{{ This will not be processed by Blade }}](notprocessed)

en
>

ru
>

[@stack(name)](stack)

en
>

ru
>

[@push(name)](push)

en
>

ru
>
