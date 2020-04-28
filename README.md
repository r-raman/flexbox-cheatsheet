<table>
    <tr>
        <th colspan="3">Flex Properties</th>
    </tr>
    <tr>
        <td align="center">Property</td>
        <td align="center">Value</td>
        <td align="center">Comments</td>
    </tr>
    <tr>
        <th colspan="3">Container</td>
    </tr>
    <tr>
        <td nowrap>display</td>
        <td>flex</td>
        <td></td>
    </tr>
    <tr>
        <td nowrap>flex-direction </td>
        <td>
          row <br />
          row-reverse<br />
          column<br />
          column-reverse
        </td>
        <td># defines the main axis</td>
    </tr>
    <tr>
        <td nowrap>justify-content</td>
        <td>
            flex-start<br />
            flex-end<br />
            center<br />
            space-between<br />
            space-around<br />
            space-evenly
        </td>
        <td># main axis</td>
    </tr>
    <tr>
        <td nowrap>align-items</td>
        <td>
          stretch<br />
          flex-start<br />
          flex-end<br />
          center<br />
          baseline 
        </td>
        <td>
            # cross axis (needs height)<br />
            # stretch (default)<br />
            # baseline - for the texts to lineup<br />
        </td>
    </tr>
    <tr>
        <td nowrap>align-content</td>
        <td>
            stretch<br />
            flex-start<br />
            flex-end<br />
            center<br />
            space-between<br />
            space-around
        </td>
        <td># stretch (default)</td>
    </tr>
   <tr>
       <th colspan="3">Items</th>
   </tr> 
   <tr>
       <td nowrap>order</td>
       <td>Integer</td>
       <td># 0 (default)</td>
   </tr>
    <tr>
        <td nowrap>flex-grow</td>
        <td>Integer</td>
        <td>
            # how much space the item should take relative to other items in the container<br
            />
            # 0 (default)<br />
            # 1 (for even grow)
        </td>
    </tr>
   <tr>
       <td nowrap>flex-shrink</td>
       <td>Integer</td>
       <td>
            # how much space the item should take relative to other items in the container<br
            />
            # 1 (default)<br />
            # 0 (prevents items to shrink
       </td>
   </tr>
   <tr>
       <td nowrap>flex-basis</td>
       <td>
            auto<br />
            pixels
       </td>
       <td>
            # sets the initial size of a flex item<br />
            # this is used in place of the width property<br />
            # pixels, % or relative units apply<br />
            # flex-grow and flex-shrink is added on top of this property<br />
            # auto (default)
       </td>
   </tr>
   <tr>
       <td nowrap>flex</td>
       <td nowrap>&lt;flex-grow&gt; &lt;flex shrink&gt; &lt;flex-basis&gt;</td>
       <td>
            # the three values are optional<br />
            # recommended to use
       </td>
   </tr>
    <tr>
        <td nowrap>align-self</td>
        <td>
            stretch <br />
            flex-start<br />
            flex-end<br />
            center
        </td>
        <td># auto (default) takes value of align-items from the container</td>
    </tr>
</table>

<br />
Links to other sources on Flexbox<br />
<a href="https://css-tricks.com/snippets/css/a-guide-to-flexbox/">CSS Tricks Flexbox</a>
