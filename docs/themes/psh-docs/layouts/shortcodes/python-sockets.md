{{ $server := .Get "server" }}
To deploy with {{ $server }} on Platform.sh,
use one of the following examples to update your [app configuration](../../create-apps/_index.md).

The examples vary based on both your package manager (Pip, Pipenv, or Poetry)
and whether your app listens on a TCP (default) or Unix (for running behind a proxy server) socket.
For more information on upstream sockets and protocols, see the [application reference](../../create-apps/app-reference.md#upstream).
