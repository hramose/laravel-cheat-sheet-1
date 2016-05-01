[@extends('layout.name')](extends)

@section('name')

@stop

@show

@parent

@yield('name')

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
#####[Extends](https://laravel.com/docs/master/blade#extending-a-layout)

