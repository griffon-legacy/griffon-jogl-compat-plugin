
Render 3D content with JOGL
---------------------------

Plugin page: [http://artifacts.griffon-framework.org/plugin/jogl-compat](http://artifacts.griffon-framework.org/plugin/jogl-compat)


Provides integration with [JOGL][1], the Java™ Binding for the OpenGL® API using the binary packages before
JOGL moved to [http://jogamp.org][1].

Usage
-----

The following nodes will become available on a View script upon installing this plugin

| *Node*   | *Type*                        |
| -------- | ----------------------------- |
| glcanvas | `javax.media.opengl.GLCanvas` |
| glpanel  | `javax.media.opengl.GLJPanel` |

### Example

A trivial example can be found at [https://github.com/aalmiray/griffon_sample_apps/tree/master/3d/jogl][2]. It is the Gears
demo running inside a Griffon application.

[1]: http://jogamp.org/
[2]: https://github.com/aalmiray/griffon_sample_apps/tree/master/3d/jogl

