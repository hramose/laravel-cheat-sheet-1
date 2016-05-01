[@extends('layout.name')](extends)

[@yield('name')](yield)

@section('name')

@show

@stop

@parent

@include('view.name')

@include('view.name', array('key' => 'value'));

@lang('messages.name')

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

