[@extends('layout.name')](extends)

[@yield('name')](yield)

[@section('name')](section)

[@show](show)

[@stop](stop)

[@parent](parent)

[@append](append)

[@overwrite](overwrite)

[@include('view.name')](include)

[@include('view.name', array('key' => 'value'))](include-extra)

[@lang('messages.name')](lang)

[@choice](choice)

[@if](if)

[@else](else)

[@elseif](elseif)

[@endif](endif)

[@unless](unless)

[@endunless](endunless)

[@for](for)

[@endfor](endfor)

[@foreach](foreach)

[@endforeach](endforeach)

[@while](while)

[@endwhile](endwhile)

[@forelse($users as $user)](forelse)

[@empty](empty)

[@endforelse](endforelse)

[{{ $escapedVariable }}](escaped)

[{!! $unescapedVariable !!}](unescaped)

[{{-- Blade Comment --}}](comment)

[{{ $name or 'Default' }}](or)

[@{{ This will not be processed by Blade }}](notprocessed)

---

<a name='extends'></a>
[extends](https://laravel.com/docs/master/blade#extending-a-layout)

Called from a child few to extend master layout.

<a name='yield'></a>
[yield](https://laravel.com/docs/master/blade#defining-a-layout)

Display the contents of a given [@section](section)

<a name='section'></a>
[section](https://laravel.com/docs/master/blade#defining-a-layout)

Defines a section of content.

<a name='show'></a>
[show](https://laravel.com/docs/master/blade#defining-a-layout)

NA

<a name='stop'></a>
[stop](https://laravel.com/docs/5.0/templates#blade-templating)

NA

<a name='parent'></a>
[parent](https://laravel.com/docs/master/blade#extending-a-layout)

NA

<a name='include'></a>
[include](https://laravel.com/docs/master/blade#control-structures)

Allows you to include a view from within an existing view. All variables that are available to the parent view will be made available to the included view.

<a name='include-extra'></a>
[include](https://laravel.com/docs/master/blade#control-structures)

Passes an array of extra data to the included view.

<a name='append'></a>
[append]()
NA

<a name='overwrite'></a>
[overwrite]()
NA

<a name='choice'></a>
(choice)
NA

<a name='lang'></a>
[lang]()
NA

<a name='if'></a>
[if](https://laravel.com/docs/5.2/blade#control-structures)
NA

<a name='else'></a>
[else](https://laravel.com/docs/5.2/blade#control-structures)
NA

<a name='elseif'></a>
[elseif](https://laravel.com/docs/5.2/blade#control-structures)
NA

<a name='endif'></a>
[endif](https://laravel.com/docs/5.2/blade#control-structures)
NA

<a name='unless'></a>
[unless]()
NA

<a name='endunless'></a>
[endunless]()
NA

<a name='for'></a>
[for]()
NA

<a name='endfor'></a>
[endfor]()
NA

<a name='foreach'></a>
[foreach]()
NA

<a name='endforeach'></a>
[endforeach]()
NA

<a name='while'></a>
[while]()
NA

<a name='endwhile'></a>
[endwhile]()
NA

<a name='forelse'></a>
[forelse]()
NA

<a name='empty'></a>
[empty]()
NA

<a name='endforelse'></a>
[endforelse]()
NA

<a name='escaped'></a>
[escaped]()
NA

<a name='unescaped'></a>
[unescaped]()
NA

<a name='comment'></a>
[comment]()
NA

<a name='or'></a>
[or]()
NA

<a name='notprocessed'></a>
[notprocessed]()
NA