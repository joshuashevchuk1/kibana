<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [kibana-plugin-plugins-kibana\_utils-common-state\_containers](./kibana-plugin-plugins-kibana_utils-common-state_containers.md) &gt; [Connect](./kibana-plugin-plugins-kibana_utils-common-state_containers.connect.md)

## Connect type

Similar to `connect` from react-redux, allows to map state from state container to component's props.

<b>Signature:</b>

```typescript
export declare type Connect<State extends BaseState> = <Props extends object, StatePropKeys extends keyof Props>(mapStateToProp: MapStateToProps<State, Pick<Props, StatePropKeys>>) => (component: ComponentType<Props>) => FC<Omit<Props, StatePropKeys>>;
```
