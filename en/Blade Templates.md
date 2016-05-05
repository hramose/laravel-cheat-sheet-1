[@extends('layout.name')](extends)

[@yield('name')](yield)

[@section('name')](section)

[@show](show)

[@stop](stop)

[@parent](parent)

[@include('view.name')](include)

[@include('view.name', array('key' => 'value'))](include-extra)

[@lang('messages.name')]()

@choice('messages.name', 1);

@if

@else

@elseif

@endif

@unless

@endunless

@for

@endfor

@foreach

@endforeach

@while

@endwhile

@forelse($users as $user)

@empty

@endforelse

{{ $escapedVariable }}

{!! $unescapedVariable !!}

{{{ }}}

{{-- Blade Comment --}}

{{ $name or 'Default' }}

@{{ This will not be processed by Blade }}

---

<a name='extends'></a>
#####[extends](https://laravel.com/docs/master/blade#extending-a-layout)

Called from a child few to extend master layout.

<a name='yield'></a>
#####[yield](https://laravel.com/docs/master/blade#defining-a-layout)

Display the contents of a given [@section](section)

<a name='section'></a>
#####[section](https://laravel.com/docs/master/blade#defining-a-layout)

Defines a section of content.

<a name='show'></a>
#####[show](https://laravel.com/docs/master/blade#defining-a-layout)

NA

<a name='stop'></a>
#####[stop](https://laravel.com/docs/5.0/templates#blade-templating)

NA

<a name='parent'></a>
#####[parent](https://laravel.com/docs/master/blade#extending-a-layout)

NA

<a name='include'></a>
#####[include](https://laravel.com/docs/master/blade#control-structures)

Allows you to include a view from within an existing view. All variables that are available to the parent view will be made available to the included view.

<a name='include-extra'></a>
#####[include](https://laravel.com/docs/master/blade#control-structures)

Passes an array of extra data to the included view.

