
## Nexus API

- Custom-built API Nexus devices use.

## NX-OS - Programmability

- Essentially just Linux.
    - Docker can be used.
    - Python will run.

### NX API CLI

- Accessed over HTTP, not RESTful.
- Always uses the POST method.

```json
{
  "ins_api": {
    "version": "0.1",
    "type": "cli_show",
    "chunk": "0",
    "sid": "session1",
    "input": "cli show # or any cli command",
    "output_format": "json"
  }
}
```

### POST Request Data Types

1. **version**
   - Specifies the NX-API version.
2. **Type**
   - `cli_show_array`: CLI show commands that expect structured output. Only for show commands. Data is returned as a list or an array within square brackets `[]`.
   - `cli_show_ascii`: CLI show commands that expect ASCII output. This allows users to use existing scripts with minimal changes.
   - `cli_conf`: CLI configuration commands.
   - `bash`: Bash commands. Most non-interactive Bash commands are supported by NX-API.
3. **Chunk**
   - Supports output chunking for show commands, allowing the NX-API client to start processing the output before the entire command completes.
   - Boolean: `0` or `1`.
4. **Rollback** (Valid only for configuration CLIs, not for show commands)
   - `Stop-on-error`: Stops at the first CLI that fails.
   - `Continue-on-error`: Ignores and continues with other CLIs.
   - `Rollback-on-error`: Performs a rollback to the previous system configuration state.
   - `cli_conf`: Mode when the input request format is XML or JSON.
5. **SID**
   - Session ID.
6. **input**
   - CLI or Config Command.
7. **Output_format**
   - `JSON`
   - `XML`

#### Config Changes to Enable NX CLI API:

```shell
RP/0/RSP0/CPU0:router# configure
RP/0/RSP0/CPU0:router# feature NXAPI
```

#### Sending JSON:

```shell
http://{NX-MGMT-IP}/INS
```

### NX CLI API - RESTFUL

To be continued...




